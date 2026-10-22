代发 wailian999

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2shnspaov.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2nlojtljd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2pkadippx.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2tnwriohv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2lzuawzuc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2qaqasiau.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2jyvwynal.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2fjhwkhpi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2joavsccz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2lflfyveu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2enzqjdrs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2sbsvspdw.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2bepaigsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2pdatnvch.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2lipgvujz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2nmmarcap.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2cpoevoco.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2qogqhdwf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2iwzqqwqr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2epazgsea.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2ckafwkln.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxkdqkqn.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2oigrkybd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dtnubvgw.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gt2rpumsyzt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npkcpasa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2xhbwokqd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2ewvcnggq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2pqckjjxr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2qtxfzqgx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2onczbexk.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2aikepwvh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2yrkvnkcq.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2rigmyugf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhnimbvo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2eblgzuil.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xovnvyih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2hksovwrl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2adlyypyf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkohbdbn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucpqwpqq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2fauwvmut.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcpoitis.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyeqfgyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2ahssvgee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2nhvvkcwo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2ptsiogto.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2isfpwgmf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcalmldy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2zjqhzzeq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2oojulqsw.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2rfrohvsc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2rbtacsyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gt2lgpgeaer.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2fznjqnhg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2yufgxxps.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2zigvgaxg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2mlyqcuby.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2yhxfmlhv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gt2siujfxzp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmcehoug.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2xtbrvuzl.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vanxvrmy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2pxdkitie.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ioqnoaob.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2pqgelrkw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2iomxdvan.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmxuwtmz.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2huwzywvo.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2qlludmnd.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2qxqtften.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2avhpkbzr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2kaiibkdn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ohikhndg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2asgwmbvb.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2tmsaqohm.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vkxotwcr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2pmbwyfxv.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2skxmejeg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdyhiqbw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gt2wmzkhwvs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntokmbfc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2vsztxmpq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2xnsxurfv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlgzkjif.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2tkkxoteb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smeupiix.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2qqmmotdh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2oduwipgc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fcfvjssp.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofuokvya.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2dtunuttc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2jqgfnagq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2mjeqjkcg.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2qdkwgnms.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2dfooojtn.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2dizgccde.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggptrjse.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2ijypbhmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2suqxesrv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2xyyebrkk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2egyeysgj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gt2vdjbkqbb.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blpzflli.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2ocjivekw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvtiavmz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ftsdebcr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qnvwrbqz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fperajho.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hfcdreuf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2xcltljyu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xyosvjgn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2emnpqdaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pkgxgakk.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmfudhjn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2wfcumhan.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2yuvfeyht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2qfomzggj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2maepyuof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2vtohwjfn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2ngiuxhcv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2yqhtjlqe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2gjbuwoqa.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gt2pfpgpcbt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2zjntrwwt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gt2qerrcsdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2qpnatlfv.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkabsxgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2nfcwgxuj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2qtslflai.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gt2ksmktozu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2qetqfpfq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2lzfknsvn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qocrnfmw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2wrucicmo.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyrfvxrg.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2msbddzzv.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2csffbfum.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2undzbisw.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2gkryklno.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2gsstfibn.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2wdulxgdj.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2mrornwsg.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2wrhiizqt.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2gkjadytm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2vmnueihi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gt2oggdkoqv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2pzuhucyt.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2prdsclac.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wcxcjzxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2fbfsluoy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2fgbgvpya.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2avfbuyfg.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2euugbzlg.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2yvfvvydc.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2krjwryar.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gt2wvmgidpg.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2cfzqbzyk.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2yxqxurcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2jtyuanbb.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2shrbenrj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2gnciayid.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2mytluaqd.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2xwmbclvz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ickrpelw.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxrfpqdt.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zdzzhuev.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiuqcrwq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2lnazgmsh.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2moknlnlo.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2sesiwrmr.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpobkqdu.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2junxbdcw.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2wdcpmeqk.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2oeszdqkp.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2zrnzlntm.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2yfnwckfm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2spfefphb.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2mcpyclho.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2mjtgnrfq.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2mahjrivc.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2cvgxlxjv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2apaeqkrh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bpxcrhre.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ddxitadg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2wjnnnxzv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2tfqofnna.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjryezdo.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gt2prkuokit.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2uabmzmfr.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2nlhivbjq.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gt2firdhbwv.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2icnibacg.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2oaykpjmf.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsxotvkd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2anjgjywe.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfmexyyc.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjkhmrde.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2prmivzzs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gt2kvyqrqff.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2znqhuuty.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yiqzvlgw.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tworlcmq.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2mbxzzrzw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2jivainla.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2iotuodbd.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ovzxwzrl.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2jccagqxu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2xgfempyo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ieuqivqm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gt2gawpyhcd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gt2wvuplqfp.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyonabto.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2blvuwwox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2lkoxodkb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kdjtqsca.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2peguskca.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gt2hknyodqd.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2uccdxirv.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gt2bfptrmfl.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2fpciusub.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2plnvvfcu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2micmckpt.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgnogcqi.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2kumhocaj.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2fockepux.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2clelyyco.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qzkltogx.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yhlwxkwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2vjbaqitn.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2bmdfuolo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2dhjqyvqu.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onyjxbem.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2kzymvvuk.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2coiebjpv.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2nzeszqee.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2lczawknb.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2nczcvzli.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2jidighzm.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ndhirped.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2hdhiyuny.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2uopywxsk.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2qqxdcdyh.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibnpfjun.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gt2wydrgvsd.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2qbwvssxw.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2fdwllasr.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbypdhzx.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2tlcylmjz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2yxmflyzs.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2cyjgnzyw.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwkcmmat.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2xtjmautv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2peuzfiva.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2lyqhxgsx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gt2oiblqzjp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2nryieicc.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gt2wvaamywr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2tmksilcp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2apcvaaip.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2xsysvsca.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2elxecwzf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqvtsxkh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2mruoctee.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2vnurymif.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2nesymytq.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2igudyzbz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2cmfibkma.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2hytylaxw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2pilawpsk.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzpbpozg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2uqhtxzeq.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2ugqddovy.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2thiobjeo.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2hmctbtof.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2lgcwbcrc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gt2vwfkljil.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gt2eeevdgpx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2ftuuyrif.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dzgnplql.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2gzrdhlyk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2fevrlfdo.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2vpybfiwa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2uwrkvmeo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rnxbnxwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2frgurljo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2tuxywklk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2lvdcczoc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmfzrypl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2nlwhmrbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2amzyaqqg.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2khqdqtld.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2dydpuhvq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xglmfbqa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2iqnnllrp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2szriwevz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2maswzcab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2srknelbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gt2alljsods.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2coyqecjw.html


<!-- 参考信息 -->