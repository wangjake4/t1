代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbgsvcp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfeldkg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eahpeboc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvnmyxs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjohpx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2esltgjwz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2itvesgho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqaeert.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfumxggg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcxuini.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jykenijw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdopaab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicekfrh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2awukmusk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjpvgjg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dqydmznb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2skuyobra.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kicqvldn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpjnwjq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjbunsd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxdhtsj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsyxteo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tffgcxww.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsttbach.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dayhabdw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjjwsrd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmamwar.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ognutqko.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mfozvrbx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lggjxnei.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2equmyinx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeyctwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zpufyoau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2flpnyahg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zddamexe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcygmqsd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slwlrasa.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcklmqyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2thmkoxbg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iynnucvq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfcjktc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dheunjav.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzlozuh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvaxvac.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpmmehz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlzzlvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arbvavsz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaxgbdj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ceclfqkv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzravld.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrafegt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iudmxidc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxxvhkd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxkhjxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2onqozijq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlmqncv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzsdmtc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfvruuv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfymddr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfbqtup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzzljgg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfaoign.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzchcugm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jykgahzp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvsyle.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxlucjl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oodgghhp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxklvegm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkhseqr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulrmyxc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvsqgow.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coaefbbg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfibpua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eumtlses.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emckmhhz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinuzpju.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meedgova.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vggwfpdi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoleuas.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeicdpk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xftlmhsu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpwtlro.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjcijxt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2walxliyk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twrtpnrl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2msvblipd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2emihevia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lozlfeqx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfdvul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqlsrqz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvbkldz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhmnpdw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znhzkwlq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skvktfld.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbupwqk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akohjuab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2unpaqsrj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoytbdce.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kddvjxhu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2empsbsar.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgjikzg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irlmkgns.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roipafcs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdmzawp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tclylkav.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ppricyax.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzivgvbv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwfrsuv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgdzuym.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhffte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmcithw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dknkuksj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oagvqxee.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvxxniy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2spazcsto.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmobjp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxakxmzv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtyutgj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2iccjfxbd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfnkjjq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ooigzqqe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdczjaky.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftgyqz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rozcmusm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2alwyltdb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgrgfuy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoileni.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ygafcmhz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haznnmjd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sasndewh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotqgtn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtkvlmc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhcxrtd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzioiztg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqcqxnr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtalkcw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tdthmwlo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eypyclaa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wmatksec.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinrsxhn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ducmpndb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruienqar.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klobnhon.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmrspg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2udcpipts.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeigykdr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2atfsuamp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfficv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ysacpasb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jujhhgzu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2axrdpcnt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2adsqehnz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjmjedw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gueturjl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rlepfltw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljmmypx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyanulxv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqgxpwj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udwbomgl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdtnewf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvzbvmt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djipcawu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dthnrcdo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2toxymhhy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtjxrfv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaninon.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifypxsg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbugxosi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhzknrj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2szxkbgcn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpafkxox.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bstauzjp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqrlzxa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjbehx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qjakwxcl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qbylvjhe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2imebdrtw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbrtqic.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxsaydk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsjzxmj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qymianea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjhppr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nistjtpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqgwnvm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2shqlsnaj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfxtejb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocarroqt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcvcsim.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zboszizz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uraxqdgu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gccacnfs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hszorgcj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmhoqdc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjctjaj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqknqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvpalsl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kojssuyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzuurdq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxamvtb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtiyxce.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2swyzkelv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvzbfw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlnctty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xutczlkl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlryibu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zorbxyme.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmoccoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohirlhoh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mldddhae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phnaoiiw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgqpzn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtzivlc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywovkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2motfsnts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2minboagl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyuggpc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2srmcuoza.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpztamn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbjsxxn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbbuljg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bytailmp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cshnltui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophsljjy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btocniza.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzcvjai.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjjyeu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smkbbwza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbbntji.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tphkudhs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfifssq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jffxdnqw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbultumh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogphmoqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bixtyqkh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyhprgp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2emdenlxh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2heiigyyr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaaaejy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2erpjaykq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scxymluz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2traqwzqc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voqhatgb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgsikg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxpopmw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rphggjww.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvwigxq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymxrkb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2novzguhf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrxbwfa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvntoufu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvestcqk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnkhjmm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyljqxrg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrgsnic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miyuyerk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfynoxc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnmisvo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsyrvpx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfykfds.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pheqdxxo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdzxsry.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2prqcfrqv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqlymku.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xppzworv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drhyfqos.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsclhkl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2btyxcgiz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zohhvred.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qamftidi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzzrolm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaiyhcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvlunbw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgywdzl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jozsgisa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhocepar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2clnhyhka.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmxnyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2odcdinsd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhauqbj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbsochj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oekohuuc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2azgupgei.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uvixjckg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jutxzufi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnjxhst.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwibyidk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervpzqiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yposmevk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hezmtarq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdutouic.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmzvrsj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2amocipzi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmcybbe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrkzhfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yheoveww.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkbdccd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rujkbavm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoekauw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrfhgxy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwzjvzy.html


<!-- 参考信息 -->