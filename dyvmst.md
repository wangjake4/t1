代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goawhxac.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prenrhka.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgvyhjt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2brmxomts.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkdaovo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbtxnoj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgtvpe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrxelmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xplkjnmx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxhqncr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhotrhry.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2thzjvqja.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsjrtra.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxqjcro.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngejxloj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwbjphz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpmcjwd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zparnshi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyszdfie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhryweni.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2igcqpnyu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbzlwro.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2buukwlnh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xccuzucx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdmwdmx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjgynsh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwypytrj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hygzyynj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irixjzyb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2enjvhdbg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2aolmggtv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdvehcf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnfvavh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thnhfgdg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcgglyz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwfqfmo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdfosl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqknynm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvrpuhq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnxylab.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxoftpr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rknathuh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nezpzbyz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fksayhka.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlctqyrd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlselqjp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnuvkfo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2snlyogyh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvxmgny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2paozuovt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bebgezwa.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rkucgtce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2unlslbei.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvfqfew.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2owrmgcxp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsipkfg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikauajcv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2udgiripq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxlhfvt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfcanpv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2byjivdel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqflzei.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wndslmni.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xousteyd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhnkebf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awhzgvhe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsntspe.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eotwytao.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahccjlan.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zihjmqkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbfdmge.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtwrrfi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obvicgkm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyfpahd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgjqmt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peqlglvn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lybdptzi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crpmdall.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uupksjgl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obmzgzgh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkzjqvn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjpmwsj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiocugj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqkhuwk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsqhoua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsejqum.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouppxdtc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpeoiqt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdzvugx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2afsxuwsc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zmovsvhk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wooqikpp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xivkgfci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tibtppya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhqqgox.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efmmgqdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhbievp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eqihhuqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkycpou.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhinsjpi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeonveb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vipbpiuu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rydojhlu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjydqhyf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhffkiv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuyezgo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfwhwjz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elxydwsg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ockslvll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdfbsbt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agoiauwe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeepxdo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzhxpgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oclmasye.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadeoktz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eneacesd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjhdaip.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxfmkui.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dozbvdxu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2exxfcdgr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjkecfa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtwcayz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smkdeyaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rnckfnsl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlkhcue.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbgzgdr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tomeykqb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2flijfwly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiyrerd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigmmpql.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtpdiuw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxujxvru.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hleifmhq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2squyvvvk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlovhdn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkijewh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zouotypo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oojrfjvj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrfwbyn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpzrcmr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nknatwct.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsupuzn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbpnwxv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oetkjubc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kydkmwbh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxcxlfb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxgzebg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckleknub.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crrrxyze.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpznyky.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2khfydymq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gstiovsz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlpilsu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ialrlvdg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaosoufy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnqehjs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnxtodc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvfdurv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrlwqxn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jxctgvqi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtlfcnn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqrvuzb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnewbbg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkhggfe.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcyassi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usqgefbu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvzsmqy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zofjktqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlhfbcz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cijrjasg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dthhngvg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgbukac.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfsrvqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsonefjr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2veevgjdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxqvaul.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahwwsdp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdptmxhv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqtspua.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinsvubg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzirflc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocalghej.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrjmqpm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jetkwahb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2afemsqgq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkxnmog.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtihmyj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oekbheby.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwghcbs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jlapakyw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqarjtx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgwkdxb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjycupjy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shgepgxi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrosyouk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfxubib.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgjtwox.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkwprjg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvreejsd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xpajqzbk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvscheu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlezfnsb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnonhcb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hptqiqli.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhjzpoo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmfmvfd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjylmjpi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhojdzqe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqrwzg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2szxjwjfs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwoehl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzdvaqq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knwhtlwz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdlcnzv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtaffv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaliqkb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ossyjyks.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauchie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwlcpmz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uillpmmp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yojlrrpq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvkjtqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhashhz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fiavluqe.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyisbymq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkansgu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mblbkxkf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgltrey.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rywytadr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjovcnsv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlhsvzo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvudoly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gabsgysj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqexagc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rffgcbyk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2boyhpkhg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuarvlxl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnayijdd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2myuenonf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqrrbbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwbinga.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xyltcvyt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2adhdiors.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbycahhl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkgchpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqooebpx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2evywaptv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhiprkc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lestbktl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqllquzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnrgfiq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrjdvte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2citupwou.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlocjqui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsmfhfv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2htoszssa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvctvfk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvetwdu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svjnisap.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtraqpro.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snzzayde.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ieswdnvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuxiqpr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielvnora.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvlvfgl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtlnhfo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dacnyhuz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2itppwdrt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgexcoj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kehaupqw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2razrbqop.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbptjwon.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqdxmgc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkafmsom.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uugvdngu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdfcqz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grdlpdak.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvlaijt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usdjnbuy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2taalqeym.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwshkof.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gssksywx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzuuyp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmuqdhl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoutspd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzngiibe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuysojwn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odgowmaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpegcnys.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2idsdqdsz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xutmslhl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbuuyr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wzexdknl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqclmzg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qflnlcwz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfjtizd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcoczuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kssgqmfu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmairoi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpgfsry.html


<!-- 参考信息 -->