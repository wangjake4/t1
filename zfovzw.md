代发 wailian999

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2qhdzcrrq.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2mmxbvvmo.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2sfkdxdgd.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gt2qoomzwhh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gt2apxebeem.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2fqpnhlon.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2frhfzpge.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2tjgyxtwl.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gt2opeupgtl.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gt2jwyqakvx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gt2lojoewvi.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2esasfkjy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2lnqvocxq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2misglviw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2sawyngjd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2wsaitsrt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2ubksgfbi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2vuzzeaek.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2loomhrhs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2sojncmom.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2gywlmelt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2spjcnlsx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ftswxscz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2xaepmywr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2jcikkink.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2hjmnesnm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2trwkcjoa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2jfgthnsv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2ipohktlh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jvezpcvk.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uexxyhro.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnjhqpha.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gt2wjefwjdh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2pazwdgyl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2vvjrrpee.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2frwfpjxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2qfolvnav.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2tvsdcylp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gt2msznlgct.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywvboqdw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2vkkpzxag.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2pubbxxkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2xbtygujx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2ifhdeglp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2cnethmdg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2hxjizarr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2oinuexdg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gt2zrvhyzdq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ommuluqq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxmmumlq.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2zchkxonv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2acffztam.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2hnzaktkf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecscyagw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzsrulgs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2yowozfpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2xrbdgkoc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2anqarofr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2ttejfnje.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlhjkukt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2tsbbjuvm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gt2kqoqwrts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2ihgcuezq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2xuvrkqbc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2lixazokm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2fmestvdd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkmoedep.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txinyaex.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2hzcqqura.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2kmwcfovv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2vsbjgydf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2onbcgbza.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2raqdbfro.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2qzntudyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2tkpviutz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2pebslrtu.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2kcejsuaj.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gt2ggqyabuh.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zolunrjd.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2sbjqvpyi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2nqjirwhj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2acegygml.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2qyfvkrjx.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrftttsy.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2umkxzolb.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2owrdjmpb.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcoamiyp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2vmfwiaob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2caiqownm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2fkaehwce.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2fvnuiyef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2dfxediud.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhykjnfz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2lsxkbkgn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gt2qctlmbhm.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2wbqlwnyx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gt2hfeaficc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gt2ddcabbwn.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2jzhmsdfk.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2dffuyhci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2ldjyiueb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2jdvufllw.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2efegxprc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ggafipba.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gt2gkmmcjul.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnpvybml.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2omrbgrjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2xirjhdtw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2gzfotteb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2hhysyocd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gt2wfjpkkai.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dxvypwmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2nzdigxac.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gt2zllobzlo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptcnylyh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2qnqipdxn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ruzkhmvo.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cawpudri.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gt2vvwknqsi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2byiukduu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2iznbbmaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2rhodpkya.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2benwrldq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zatusnaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2gqweaqwb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggbrkjrx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vfdvbzlm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2oyvgufzq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gt2ynlddync.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2odwfupzz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwlflxvm.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2jmahajeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2xgilvggy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2rsqnoqyr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2mqosvxaq.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2iwbiqnkv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2rrpwrmmn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gt2xmxkctfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2vmunppxa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izhhnysv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2mnqtnffh.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pknfhqkp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2isnbvdkp.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2uixzwvvm.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gt2tyuettam.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2ltzldrid.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2yprkrmdv.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2rsfgstto.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2qrhtunwb.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2xfgkjhqm.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2ohjlrzdu.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2cuzetywe.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gt2igtrbaza.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2snzigtqw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2pcvdamkl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2rgwgrewc.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gt2eukzgtld.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2dtdqgyll.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gt2eyesaeyk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2qexwpwcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2nurbgalg.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2pmzzjfiu.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivcmaard.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2jfqznmce.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2dmgkhowm.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2yhpedozz.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2lftuxdjo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2cstcnwhz.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2njslzugr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2mpwtsnva.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irnkkqex.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2sgtccprs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvgixqqu.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vfyfgyvu.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2mvqsmajf.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2sveiqfbg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cijvfobt.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2tytckkis.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2zzyqjzpv.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2rqvrmywj.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2qcemiesa.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2wayockkh.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2prpfjgns.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2gpmuhpnc.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2imgjkjfh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2zdivqsgn.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2ukvenngk.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2teiuaoxc.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2sselhpxi.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2brzznglh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyjwbvuq.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2gidywvvy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ulvidmqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zssihkdo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2cjzjrlec.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2igsffjkf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2xcfohdlk.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2owgljokb.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2flwwllis.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gt2ypeubkdv.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ersqdfkw.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2xsmkvigl.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2iynjuuyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gt2surxmmhc.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2ddcsujgb.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2lqcmeagf.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2ngztizbd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2yfltlgay.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jlqreabn.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qbumpqdl.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvgjswrb.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2kdoushmg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2whawnkci.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2ijhtohul.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnhzakcg.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2evxarwdj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2jznexoki.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2nkwvheuk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2pqjqqkas.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2zqqbotdd.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2cymnlsea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkmhmirv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2kpckraeh.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gt2kejzbwql.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gt2xasdkwby.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2vwqrpdhm.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2zrpsamda.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmuajvkl.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2rundabyo.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2jenrmhzz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2vensxwhm.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2nlbfvocr.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gt2vdsgtknf.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2esltgqzl.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2xqhdirye.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzrxapja.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubgpdbas.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2uunnsqnk.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2omruzxce.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2adwjpvjp.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2yngvymlv.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2qzrrsvwe.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2etwbwrrj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2awtvwonm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2ssijdlvi.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2yjshrvob.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kgcsmody.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jxrrhuyc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2fjaweixr.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2yjqgvdkw.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2lycizbkr.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gt2mbagbqzl.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2wcvqojzb.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2vdjnqtlg.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgapgyea.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzctezhy.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2gerqctcf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2ydnwuloo.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2vjqdixry.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gt2rpfpmwtn.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2jcmuysnb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gt2sahvhidl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2wjzjajue.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cseeqjhb.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2wscwvkre.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2fukuhhnp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2tjaoxuzu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2jouspxvk.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2pmruiqun.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2nzmtiwbe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2tuqjrtoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gt2wmpdxuiv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afwxmjnh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2mladxagn.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2efkdbqoi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2tmsnzald.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2zvabdjvs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2zsmpxitc.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocipeaji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2lmztkmms.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2hdgjdrkg.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2swhbtbzq.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2unxdxhum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2mzzsrvyb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2vslpandc.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2tydbdeda.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2izfhcfam.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kvexryni.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2hapcfekj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2dpopommh.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2oqxomtvp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2sywrmlcx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ozpcavls.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgnimfzi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpbouztt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2gtuxtqpo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2prqtjsqr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2xhxegzuz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gt2ipuhvlot.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gt2shvzfpgx.html


<!-- 参考信息 -->