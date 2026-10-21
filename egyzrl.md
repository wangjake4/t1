代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtqylpokzi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gteztowdki.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtihkinjwo.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtnkumefrh.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtawnrcrtq.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtfrdcwxhn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtbbshznge.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtyhrukoeq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtqyjxkvag.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtrlfuweam.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtujjijnav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtrvozesus.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtyihlemoc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtrgaezbrm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtojmwepbg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtlyhpypke.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtypghspeg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gttmwhzknw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtkiostvgh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtemtfkkui.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtmsauvuyi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtjhqsjazq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtlfxxgezy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtmdqnpsve.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtlfapktec.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqlxtqvrx.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtxneqshzo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtptijsarm.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtvejfhgwy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtwixvgbqa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtsuspaebs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtnqvopavf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtaxympbro.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtuhcjrutv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtuejyhpyb.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqsixklwt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbpfhlpux.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjtsajqxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtnmjpafwd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwbvlvi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtuunuyuzg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gttizfejni.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtgyxnavyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtvwuzqhmx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtosomkpxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtokqtpfcv.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtdyjldurq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtocmqntma.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtvlphbemw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gthimyteoh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtckleqhod.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtlfpsruis.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gttqpvpegb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtwwgiotzh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiyljpad.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtzilvxavm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtuefjgcyw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtizpvcjet.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtvoxtojni.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtubirhdgr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtgnwmqwti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtectevttv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtytgkwbqd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtzlqecxkk.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtrvzyhkdl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtfzitfsum.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtevidnbyl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtegeaauog.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtodyaknnx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gthikfknpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtbcrdzkae.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtupiywguh.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbhrfspwn.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxixpyaq.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjbixfyrn.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtugiqdbkc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthhnqabpm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvjewcbyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtqglnvshg.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxwizfclg.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtailryiyw.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmrbqwhto.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtzdhdlqey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtubfvroig.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtnuijalbc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtxxgcyuii.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtowwunlkt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtcdgpltnm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtkmmhnapi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gttfeqvign.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtbgdncbfq.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtrruytqec.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtmuijvphx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtrnumltba.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmukbiiyd.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtwwdggava.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtpyoozjnf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtmdgotzhd.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtmszdxhab.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtvowgzjrw.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtwmtzigww.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpihfvdln.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtccumyhyf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtwsnibhwv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtvmfhutzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtamreostt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtvrelgpgj.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdmxhnmvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtobwfvxhx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtjqalwrtp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtomlzkdow.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdhrpymov.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtrbjyjvfg.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvoflsfme.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtadqenqiu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtukdxgvdj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtanprgslq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtxzkjrpdo.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtwcnnermj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkwovuuks.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtoqvmqkth.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtegxszwwv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnjqabsju.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gttosfmgus.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtrwifomqq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmwjltaid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtsagemjcj.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtapwjhutk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjwyioaa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtynxfgvad.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtjmbywhzg.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtaxrucbam.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gthlkrqdsn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtrawclwot.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtzzjfcohu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtucrbupbs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgdkxhyyo.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtdemevtzd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnbkjpksc.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gticaoffqq.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtqrecsaub.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtkpckjcyr.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtghqmlbal.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtjrsczneq.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhhwtlam.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtgzthmvcp.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvplhyfse.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtnbsgljgr.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gterirpdab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gttexslamz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkeotqacx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzpbbvwha.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtqgccvbcz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtcnhdeqbc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gttotpqiqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtctrbtdlq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtzmelrypm.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtxweivrhk.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gttutfemyl.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gtragdssnh.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtndkanqrc.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtkrbgfohs.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtvfsjkezl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtzeavxnch.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtzvljwcfb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtdmkzqzwc.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtzvnrbldq.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtqjnlytpn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtxegiilxi.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtgytqtzzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrywnkhvi.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtidgsdrpv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtayeszqgc.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtqditltqo.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtjuluqtsi.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtvuzvzluc.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtaitxilnk.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtddzewowj.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtzexiuudr.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtsbbneaso.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtkjlewurb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtjkwbusdh.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtkbdxsqxr.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtmaxssghc.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtyzjvpwua.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtxghnegha.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtbnfgcgum.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwsjybwrh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgamspdou.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtuwfxfhmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtryqdvseg.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtgeafriym.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gteaoozadu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtdlnlazce.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtxsqqymua.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtprwctnos.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtbucccntk.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtidhmddjb.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqcjfxhm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtaczbshxe.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtgyxpdtov.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtmvhiylst.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtkjkvmsoj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gticlxqwqz.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtikrnwppt.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtdgcuypek.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtyklzcffl.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtqenxkxae.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtuokydqtx.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtjtoffudu.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbotcxqo.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtmjcnbexj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtvdkfzhse.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtausltibv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtustzstgn.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtvxagpzwl.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtaejscjvs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtgmvunpys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqfckxswt.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtxpicepfj.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtbwcvdwxo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtfokgdmdr.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtpqviphlf.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtguzgtktz.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtmrfdzbwd.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gttuutmdlq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtdzehzsve.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtnptshkpa.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtegicnsuz.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtcifnbqun.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gttczmmxmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtpjvjjppc.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtljetnnfe.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtzaediazd.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdynbtxpc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtxytsnmzl.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtxofkpcpc.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtxfvawydp.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtccvmmdjs.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtvuvnjbmv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtaphvwzqs.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtfgzphzsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtdpoqknjf.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjwyaqtei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtftoeghps.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtfpubxgbi.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtukckpnsv.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtakcisncj.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtcplhuqjw.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtkzdlnpxp.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtpwwirbxd.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtaxxrmmlt.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtqhzdpxge.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtxaambzev.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtiqxjjddc.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtpcinzovw.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtkpdjgbzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtqomfjysj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtbsgxqoah.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvhiwbgs.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gttaewiqod.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtpfgqczka.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtihjvsvlr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtbysyksth.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehuhcbqd.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqogmzsy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtfoepksoi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtzqzdyoyu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtxidzkfzb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gteavxqocc.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtmlikmqzp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgebrxhc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtclfdewid.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtyadxkbub.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtycjjaryz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgldpapue.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtjaozajwu.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gthfekjuju.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtqeqhjcsj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtnxdeocqt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtbnjwnnef.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtckorybak.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtiriaqzox.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrbprvezl.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtojnupizy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtczasifwl.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtbjzagsyw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtqrrfttfs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtehsbhunt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtmmlelnlp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkccotcph.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtstvpnace.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtrvmoxbhd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtltpdapsq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gthovctmwp.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtepwlglul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtpdtrkyfb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtaszvpice.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtdswnbhdc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwdavexwf.html


<!-- 参考信息 -->