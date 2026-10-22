代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvyjyey.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2urutvbvs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqexhsb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2knnoywid.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkacfbha.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqadyydu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcigda.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaptfjf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwsmmux.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjwjlhn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yauybfwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nljzogkr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2serahndt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgpivzh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iunxkqpg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2apgnxaac.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yabhkane.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwelezn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2liurhipw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuzvvwr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzmatqx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfouthve.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdxpbsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiifzzq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lobfyirp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xstxgvth.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrstiol.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhprrnpy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzicoqqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtdigje.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2riwvomvt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiywdqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lurclyec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlifqedr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccykylfy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpxpaqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubemkyvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywazxomf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzjpgsa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vchwmpqc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2delroopt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxfpuvh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlujlkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwaibqw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2orcesuyw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndueseee.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdhdpfh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mndnbceq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmignoo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfcxndk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiycata.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhfbnxs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dawvlhel.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nokvzewz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfivueli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2merykkkz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsmrwyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sirranut.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkynfsj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfhvhrl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoseadlk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lunbdqjz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyusizni.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpswglwk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhqpotu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuqvgsi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqguphgq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkqzoms.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2crblgpnt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiezcgk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ciroctjk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tksnddzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkqwbqk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2luyktsak.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqdnxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dexyzjkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvlbado.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwxrbwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udpdapvo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lobtxrzi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2krgjslnt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdchyqa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfxukb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoyhknm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mphrovdf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfnddra.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyekrwrq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdraklxk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvthvifu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkezrko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srorjjfq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudhhgj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cglvsctu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxjknil.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jahfakro.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ancpfdmj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpmqwpv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzucqij.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbidibg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwticnz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rilgpmhb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnhpvvw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoofabbo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xbplmwgj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2roesnptv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxofais.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoedwpu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sygoubga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpratgd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtpckaa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewhyjks.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydallbk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prfokhbo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojysdakq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbxyxr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvosdcn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobdjdk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkivpel.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xejxyehi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rchxktvf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emslknok.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbuvozr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsugjzii.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgvinlq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oojjbrmf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2klsppfvf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhycwuw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelpotog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnvyftc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkdqxqs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sjloalqw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whfriayc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgtyfkb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqklkrw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2txxjdftz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2khhgziwm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lswfpumm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcexwzqd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiyfnxt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsgglbm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhzykqa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2apbbuwyn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqnmqxv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdefwbi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wggolhxc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxayryc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xptqceft.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuuevtv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2juqreaym.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shqclnop.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzomggga.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2auyzroop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpgxari.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2munlzmru.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hakcmqiu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpcwiru.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmdbwln.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exhkpntp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfevotel.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeqvgyi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uctanwms.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbjofgc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2twkqhazk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjewend.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iriuxhqy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jgndprrv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ewutvdcx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2brgpnetv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdrwrnv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ieryxavi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwbivya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anoqwogw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcuquns.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brdxzyqx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiormswj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibrgdlr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwckcd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiabepnx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2thbmluks.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tdleahcv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsigybt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqssuwg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzbcars.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmubkdu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmtbol.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsoiciq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txrqlkuu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mdikwihs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwgesrc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxyqfxd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ubouxwln.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spxefdya.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qycsqsrg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfyzpx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kachapuz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gansxmlw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sudbjezh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hpudnury.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ncowhfdf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjvybrj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuofbkbc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2senustmc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsexdcvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkabuas.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzpimxp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2krezscqo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiwvtsn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clcwexqc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmpwskq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikleuoqo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2efuaraca.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgmmegl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmxxaks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzprbum.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtwhnfk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmzizdw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxjfqo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddosnth.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwzsywh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2asxwqwur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaorrvv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgtqioc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvmaihj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsirdqo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dhosptnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iglqpvnw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pveykrew.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqflugtj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffdjadq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrtcoae.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arvqicnb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxcpaw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhdxows.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2befibqby.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhzwcew.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzyesxj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2midooopw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeakonj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btcfzzqj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqplrneg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2masqdewd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoechmj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyywipqt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfouiorm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpwmtvx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmpaquk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzrvcui.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2maixgjyx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoiuiuv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dneckauy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbchxqu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdvletl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2puioednr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbinwfyc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxrxdft.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svtwmcjc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noepuigw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvkycwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pccwrjll.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwleaot.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfrgbje.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhqypwo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ogznqzgq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmexweg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iknxzkvw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nihmfqrg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrwsatm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeisiqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnvyjgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvvzgbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwujepi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hubvooep.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwcficn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpaxjlb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdvsqwv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ndugwyez.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihtsfjg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbistizw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibyevqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxqgblw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nxczswmi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtyppxd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifapqcbd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnhajmk.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlumfcwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2snggweak.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuvfffb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfnwocd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wakhpwoy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjpujw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcavqtmw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tliionfu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfznrdy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdpggf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2viubqgce.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2niikkzfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fezjzawi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2idobluxr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gveckfss.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fznidfjw.html


<!-- 参考信息 -->