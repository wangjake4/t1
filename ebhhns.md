代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfkdbic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2abfhktfj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrfbbsk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjarleqm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2stqelfvt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqstmqn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhksxxku.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eslpqmwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjhscck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdestaq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuomhfj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmfrrve.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2imwmgzxb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuidwxm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nolobnie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiwqfvw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wmganobm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgqfwpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwlyaou.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhljdcs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvpiefh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2brcchsic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2levustga.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tguwrzis.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhudyjbu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadwsvqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpdbpfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzjxpo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isjqctmj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqurxa.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krrnqcit.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzdsij.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbodiwqz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oewwatzy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxhzwsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvbmjug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqxpgjn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weaxjjft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvflqof.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hazpnfyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjrkfqm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqtltx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wymsvcnq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrnapa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mldhkxex.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdropip.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvrfiqh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrxiorz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iumyfmsq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bqipbrxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiefblj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeucgxl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qawfrdsl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkovzrss.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avbxbtiq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttieepi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blhzuvkr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2asuuvmtk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhptpky.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olvvcngy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gierxjyi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fujfaacr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlymiowq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvuqrxe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2albqfkft.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpixawl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprnbdrt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhrdvrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eynjvjdl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdeifyk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlgsjqb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2huovoukw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dusascnu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2genndutk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhvzvwv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hetmbwuo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqurihiw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhryqws.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dhosdddx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcpivpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iknrzcee.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdptdwd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkicvite.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkebsiaq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvjsbwd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2riebruln.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2quorkqwm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdajue.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwzlqn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqdpsos.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqefifkf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdibdvt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjlfbwv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2huibjigp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nruztauk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwgylut.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uerxgght.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrxkley.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmvwoab.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjhquua.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxqpcrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnubxgrk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2awcngyic.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkbflkg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ontdycmb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2reglspyd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxoqukj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eaplzcst.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vigztevb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2guqnurop.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfogvqt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kxifcump.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdwnqeu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzeulyt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgvlrgv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxnqdqg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjpqeiv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxtkiqt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grovqwex.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrasttr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2djsdsqam.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbhlgkn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyedrao.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzexxvfs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jilzclpm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjgijol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2icuwpdmn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmpujbm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdzpgm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuntmevj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwswmmyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqclgmw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzvzfvm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2apisqsrd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmfznci.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwgvcbe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sziamtdb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhffsw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qscqkxvj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmjezdf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilbdfq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdjdzou.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fvggnjtt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbongybx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyqcymv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzciljvu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wemrqyfj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jubtlbsq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqbwltr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjchgmn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lepfumzd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcebjzh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbenfhw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyraywyw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaorfzvm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guufnxwp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvkrkfv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqouckw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgasggd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flbpllcg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzgfvzx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfehyfn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bckecrpi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqnpxql.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsqsolk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqypssa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaufdwv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tptckjmt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vqucmrpx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmyols.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2voxoewfy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2seioghrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdgueh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkzwexv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mliftnsy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhcthkv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigbnzqc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2urjadsmt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2emdodufm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxelqza.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2riqznwts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeghsel.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngqpfjx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpafsxji.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2eipmwjne.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsjhzc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxriho.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jmojjqzy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiykvms.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmugocao.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbfttme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wucywtfs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oierijyq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qarnwdgy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ufazjpby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvosvchd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdpgjhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokdidvk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fbllmuau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbqccyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lagmlujy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyhpzpl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtrbrqm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcpkouz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhzvrfa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2feftfglp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjdfnxn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2puibgzac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpsumak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuwnwpw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rowpwhnw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oprzduoc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isksdayq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2roiqldgc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbbxtqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiisokou.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkqsomi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2womqfzuu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcqyonk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzzwtgl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wahhvdth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeoltnw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2durusnxb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxkorwj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxkkgq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cackbhly.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2timayump.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcxqayt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oujifgup.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btqjlnjf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obobqhrw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ockqxszq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pluqahxo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjiswub.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdcbgz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nodiwvmd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csihhxkb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoxfknn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpksupo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xarxvmib.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rritufbf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvjwook.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yegdivhm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwcrakj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kjphwdaf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukbocj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xjojrhmf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtupejz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrhzryl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcryuqhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultruzph.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kuysdlrs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlrpwin.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxqetdy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnghhbe.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmdbqgu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwmvgqn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfusggx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kptpvsgy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqrpach.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxupxyqi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnplhvr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvvbrqv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2madjrowr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kxslojiu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvnrszl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqckluqc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2amsctdxx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrtskzq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcnrzd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxlqwdb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ucryzbik.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcinkllh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxtjio.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttouqljm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skglrhmq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqhtxgh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqluszrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2toglntqz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxuokle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hygkipcr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhamxcet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qlydqeqr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpigmsx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuwynlj.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfjzypn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmggrwoa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arutpeib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcoxaam.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhxthjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smbonwut.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxmrtiv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mneiofzk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hioqkvlo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqjoah.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlmnnxt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2eokybdjd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqsxiwp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflfkonk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xewtweux.html


<!-- 参考信息 -->