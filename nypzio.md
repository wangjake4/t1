代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gthwaigpkz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtzqargywz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtoopyzgeb.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtvbujivty.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtqpjyomdj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmvibcxen.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymckuynd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtynwpztin.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtvdqfgbye.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtaxcnvkpr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtmlumnhvq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtexvzyewj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtpyyuznpd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtguabwycm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gtyithzrxz.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtcmwpxibc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gthuwgcrrk.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtwufsqzhr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtejsqsbfu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtcutrngzm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtckttghyn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtsnlppuzb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtdhbzzpyw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtyyroprmh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtfbtjsuej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtzalqbjgi.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gtlldxrroz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtpyetulnn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtplmcjdhs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtztnbdirx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtewtflyqy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnydvcdc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtkcinrcoj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtavrdlkzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtbdfckcnp.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gthymkmlhd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gttcpwgoyh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybhjomor.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtfpvclhvd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtosqxiugs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtslvkhnke.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtkhyxmpqn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtfpgbxrpi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwasvmdq.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtbbhifrws.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtikuhonua.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtcgorvwpg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwepyxalx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtaejiyojq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtpfcpfpdh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gthgjsqorm.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrooznrub.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgabowhiu.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtfgcsbeay.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxnwmdjjw.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtdmdiskrd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtjulteunt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxnplmocn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtojixskdu.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgzwauwwt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gterdauquy.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtcdhmymnf.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtseikzsiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtjdphrfzs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtzzkhrwil.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtqbkkhtlp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtcqqjmwwp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gtvgiiyrpb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtlawkkcpg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtiqotjrpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtlfakjlas.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtndnizlvr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtyzbbdiyv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtzgpimlzw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtzozkdesd.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtogcdivoq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtbgzkglze.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtkejkttbx.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomiqugvm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtzdmpdvmo.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtiwvevlme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbuohgmcn.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjhewwsxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtkmtmntyb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtwxxoewmd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtpbwwamql.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtggwscxjm.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgdioksir.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gttqtkqorb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmqeiglf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbptjijlz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvypubcts.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzpjcdrtt.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxnhybqsg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gteeobapok.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfxnmdlut.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuvtzmnlx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjzflylyz.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtlrwqvdmn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrqfdadvg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthfqcsqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsmedhxxp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttgwamwcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtldxbjfbb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtggfaglrc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfltvmwug.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtpnyzsype.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtjxhqysud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtitpycdtm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtevrhnwpj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtowtprabn.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gthabxqasy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gthqdpvawa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtbapnhsot.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtdohwqkta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtioakbnkl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjwxigymm.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtsgnqeziv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxmbgahq.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtbjhdaqdc.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtomgpavpn.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtztpiytmi.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtloirwkhm.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtixypvajw.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtaqhrysmz.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtkkwutzle.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtbqsuckua.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gteswyxegz.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtguvxfpxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtqavgqqcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtqrcjkdvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtmqjsxbqr.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtclkidoyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtekjsvcbw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtjmsjumef.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtinnwavfv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtngsvkkbj.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtfdrvxynb.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gttrnulhbp.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gthhrcywpz.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtvghesotf.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtgldfywxs.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtnmpofxqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtafnrtrtw.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtpdgvpizr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtibuixino.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtrdkgzksg.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtanrkvnck.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtsatrduaw.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtwztjepjs.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtamigupja.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtgnlfwzjb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtqkkjrfip.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtjhyfjsqo.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtjfdajrwb.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtllwnazxt.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtjyvawgxw.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtzqivlytl.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtsvgzskpi.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtjsnqzivq.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtpahshdpa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtjcoumpgv.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtzbvomfrq.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyuinpaq.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtycwoykdh.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtubzploig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtxukjnibn.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gthvjcgbxs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtkglgvygu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtfmnvuafn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoczokucx.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtibyqdwwv.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtpqlethzb.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtiepdcrtm.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtnvrfsgsw.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtcjvohvvp.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtyitinrhr.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtgwkmpvnt.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtqmctwmyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtojiqniju.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gttlxwnkuo.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtdzlhjusj.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtmaonsdis.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtvlsozili.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtfgxeoxye.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtzsgvvsck.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtbwxprtrt.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtnqkhheqh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtvzicegpy.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtmhrwszfi.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtbfuyvyqb.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtomuuimdn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtecgragea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsilzpspk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtkztefuim.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtktiydfzc.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtfwmpdrrb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtkdzplohc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtuflnuyej.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpiudaaa.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gticvljjnb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtlirniwwr.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtygcqrmmh.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtsxtcvurk.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtuvhvcuuw.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtvatistme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtpnjajszx.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtgvtmdxxs.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtfnvljsuq.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtlcrlokyn.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtllfwskkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtrwtnuppj.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtovzyhfal.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtflremnxz.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtxoaimcvi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtasxbxsxz.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtbvaymfjx.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtlezrzzke.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtuqbazcjm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtjwkbfyot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtpotzpqci.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gthrzmzlet.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtoetqosks.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtctrukxlu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gttjbdmacq.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtftqmrlls.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtwundczzb.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtgouyqpci.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtiiimuhin.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gthavuzuji.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtooetargb.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gthwtbovpf.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtxhkejgfw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtaoeawzdi.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtapvbetjk.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtdzrckwok.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gttjopieug.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtmiyqmvtv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtevbotsyy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtisioflys.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtgvenbfbr.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhxssuup.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtwkgnkjbk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gttaryfhav.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtdjdyvxgn.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtatqmzrdg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtvtncqqwj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtcarefpmw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtjorecs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtlxpxbstj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtkjjcobpq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtebriospt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtgqurmehb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtahcrtuuh.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtavrophlw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtcjpmhxtl.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfexwamcl.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gthgwuzylv.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtwoswmhcv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtyaucrqee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtwyeowipx.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtkqaouhpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtlfuxtnpv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsbmngdav.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtpxdmrjvh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzoyfokcp.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtcxuojieo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtvvsvnmgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqnmryxjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtdpbbsoym.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtmgbjngom.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtoxssrlnn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvhtudoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtihwupdsm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtvdtzmfzv.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrgwibrc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtzxrxzhxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtbmbzgtpx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtfukxwqig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtogxkwxgm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtdmpulsnj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtwjkxkduv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtncupziel.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtjakhvapc.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtieyelewk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnepgrkpi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtmttmnzaz.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtlizjifgj.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtotmjejfx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtiuavvlyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtriwhizyt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtifertvqi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtwulxdnwt.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtxxgyzqkd.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtoiwflqsk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoivcyzbp.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtzqsorvka.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtdqtoqtsu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtrsckecee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtqdgtcerd.html


<!-- 参考信息 -->