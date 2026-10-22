代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqbmejf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uflazmuh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjuwkhz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqraarck.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwuyehq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaoljhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivltwosf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjketlhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2giysvfsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjmlxke.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sctvrrnv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vehijigu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouddsthg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbasitoe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaogliyi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsungwjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwukvzxt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjprtzo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2devewwmi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyllrmv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwnkagb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khfheqjn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgupjznp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmlymny.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sggleowe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwzixis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nflnhicp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chknsezz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vukvlyyn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cevzjacn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzcwymf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlpvmqg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzroekn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egsqrozl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qogiarfu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvkyvkx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlhaghe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzacjbwc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xixrwqwg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbczfmsk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjacnbh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwrphpr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ochgvvip.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdvlgng.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kplwhdir.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tagfoqam.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltgsdut.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhplmdt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicenawb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpfwgit.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mriclmsv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrjzdmp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fggbhyso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2efonfvbn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgzjckw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsjcpij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joidcymh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qspwkzfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqjoevf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpdpqpj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvcnfry.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inurscyc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knkyplba.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfysgkts.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkdkqyy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jscxgfdz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2stjczvob.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzoqjjb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axmjjhpl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2myzznjht.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzgjmyx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdyngvo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkrfsek.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhovbzh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcttvqn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdqkigz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2falvbmhm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgpjeth.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2joumfnoi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtiobuj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdqttqn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjxurmm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lppvrhrj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyptjdq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vypyvzzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2drgokmro.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2topjtvgd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxpkdlf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwlnsa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuvoplg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuzmpgr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbxiwd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2joibklzl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2asdigpsk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmclvpf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmetvey.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pheafknn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jymsqxpw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mudofnis.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpsivh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvazsbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqlxewu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbgeafh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwjulme.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xewfwgds.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjjbjyp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiihvrc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afqmhpaj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouakxvtl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfmohmc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnsmqkx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmuewlr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2esqqobqi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rimrrzmv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2umccxaob.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlstyqad.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2byokwnas.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgybzquv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtftaxli.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qetjvriy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tscfrdkj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fypfgica.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2chrfrlwf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnvjcyj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jepqrdia.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2immzdwpf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aglilvhl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exkgfqyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmrcrmp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxdcssq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2semewlzc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfabcpp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2egsipudr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnccltxh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpfjjtc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrmtiva.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chbvdnry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiostml.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuimtsu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihpneeh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbxjtba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tznogces.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlnxnwu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2shgtiifx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhbqhpj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuuxnxr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fsieceum.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxcicaw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2owamwtsx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bznicoss.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzoscvy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkboslxy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzhozwf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viguzahm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpuyacf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kytjmtqa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mryjmszb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eopgljtg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dexdihhk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfihevhd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvudxdja.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goyyqoyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gprcimsj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eamlrpcm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbseopt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjbqbqk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2srjbtfgn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuunqta.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrngtkj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqixxbx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pokisvvf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmuubsf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2krlwikhf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvkukqm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhjpbhi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mivhxlrn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2grdejgee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvwabde.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtwkzlz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2peblitxx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrplxff.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xolirvdz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfxmjlq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2meorfsbs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxveoige.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2omrsawlw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzpcqda.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqewyjm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlryrse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txpizoxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwivube.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2spsvcfpe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bueygvcu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcryuziy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gclkcjaj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sabyroox.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbueqrwi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2slugolxc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtugiv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2amkzavhu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgubkjd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrbwwvk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdwwxxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osqdqpfj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gsibyihg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edcgllfg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2drpwbrvv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mobbvoyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywizlgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcpwxyl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiheoqqr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnnwyzd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhvegwm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jthmppcd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcqeytp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qdifeojw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmynxzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpwbgsm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euoeboby.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdmmvvm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpukfks.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdsccvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaqkjkc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnutmpz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdxkpei.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamjvfe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2soupkkty.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2trsfhljr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoakxkw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2afmrsgmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukonextg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdagyztb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzetnox.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjxeksk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzxqecf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaajhhb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nadsvhoh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oichfexl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwkoqat.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2skfwrvne.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfcxhwm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euawrtcf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdamzdnt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkjsyao.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmykbdi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dummkjly.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoaknbm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkuebnm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwohlsp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lhczjglm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itszjhah.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wklvafoa.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxgaohq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbqjdgi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hovwiyyx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaehdmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzzpvsq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkhfpws.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2woetaghj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2thktgizk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbxlqbr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeygopn.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthjplkf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqtvhmb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmoyfid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpmurbv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2doodmnax.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxlbeb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqzzzoi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lixyzsrx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkeyxxs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdecbrw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjckgtr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uocxqzqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlhhnpa.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfrnjaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2inexwyra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvndkhw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2irbjetvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uedrfnob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqfzrzc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2eziqxvne.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoktzccd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabwvjlx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwejqra.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2icgyccna.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyzamyk.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pjggcgfr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcgbtsb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiqfqnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrchcai.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ullnirwv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbxddsi.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbyizh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnbefvb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpweitl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwcuohq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytknty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpjbupd.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwqbfkb.html


<!-- 参考信息 -->