代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgixtnen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeojmrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyseirmp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbdusgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qodizxhh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhjsdal.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obmrtpge.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhbada.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2knhuqale.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgvpjie.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaotlal.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2unqzmthu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2adtvxwtz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqojpgnu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjuavmo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kifpskvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xletcafl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnghogj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsmzfws.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeghkfz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmmpdgo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ciukspyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvugdyei.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjbduwq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vigzphcx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liaxntok.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsevaqvz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2louhbvby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njecdezf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnslftwr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqruuyua.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwabvkh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgwgpdm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rocnkddd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvgzbqa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhztlin.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qtetniqy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luyprhmv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggryoqdc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uyghiclp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdljpmq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iygaebql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhwjuhs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbhpcdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2siorgmrs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxmdorx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnrxaju.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2alzshiuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nninemgr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eoutgnlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcsuxvn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxliurac.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qptlzhjp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agnlofga.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtafrioi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tihsvver.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqapip.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yguptsof.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ricrtcct.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2galpmkar.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anoobrob.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2souzvnwn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btpfhkmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmorhnup.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cytasmml.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvthvec.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtgkmee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzekwyp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfqzniz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnegbo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhgollt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggebghlz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlcnqmw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjecgbre.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jseerjqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhlijgi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdhcthn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoazkhf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbpeka.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2olpiuxnl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeylknbm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcrvonz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwphwej.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stdkcaag.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnlebpx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzdyzsx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclmnzg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfbgtjx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbfcljn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efmpeltc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tamczqyb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxbqgbn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hefimixd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2btkedvkd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iaatybqw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gselrbbr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2utjaumug.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2przuhevb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtxqlbw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aerepydb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrbjhnl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjevuibv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjcguar.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktysxs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kklobmlp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2plmmobnl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovucnsam.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpnmfks.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2slewdrhl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvszffa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2psgadyjr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvudapqp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgjnulh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhmeeiv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2foejauqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oksxmivn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhsdral.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wikvrjiy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwfmzwp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoperfu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fttlaost.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djrccgkt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyeyfad.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfsgtmk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2chnztdcz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeygjbkc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mxozybrj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xupxstcd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uevyixrk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yixxxcmk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyfsrxy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlovnjut.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2brrpdmpa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwdvywy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwurkrk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbuazwr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxleic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cvscvtfl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wxylkruo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2suarbmef.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rsljvuqo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdapecn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhmvqcx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfufyver.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdbcsfb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ectnalzk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnrhsts.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgchqiso.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfsglzc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uciupatm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqehcpw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uysigues.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfdhnwi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwndyduv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfrscqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhvilij.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebgpyot.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmmaklj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2etakvcms.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeyjdhi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrrdlvk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzoqxpg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhzhzzm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2elhjgtqx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vfajyhdn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2naircqro.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzssdoy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjatxmq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjgouie.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bqohcszr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2beoekmzw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqomejz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhvrnfj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2renthbzl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzcbcva.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vyybkmjw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkatjtqc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tgduuogz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2prqutnwb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjvxlpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfhmomw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uveipiua.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfqsfzy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjiyleg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ldesjknl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxbljeg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjbndvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtlkrnn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytuytyc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmygjj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaxljnt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdudwyyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2defhxxje.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tozwczgv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hruemqvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iznsaqdw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvebqnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsunonfy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmsgsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhwhqln.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbjlkf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgccqaia.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmahofih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txkcgeao.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sapfayju.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnoktk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrnnwut.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sfukwzfu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jivincxb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iodmgoga.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lofgtfey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwztbmo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phoahzla.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcklxda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnbciin.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdpxfd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2prrauiqx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmejwer.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbutrcw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvztxxu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgzvqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuxwqqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nishklch.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ootdsdyo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2omffnxnk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ephsejdu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxwqap.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbgpoic.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plpiztua.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weiqofsf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmejofai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2agarzdck.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfouipc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjdwosc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nirfvvmq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdkqhw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlikfvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlermmp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdceyti.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqtogfd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sillbtze.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgcuxjx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzcwwsq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmhijoa.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdjgpjt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjvurc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2amvqfxhn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2olfwxiof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpvnyyc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgatffhb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtkkpmw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhgvpkd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tcikgmyz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmndlquz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2obgrnisx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmmfvcd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdbxrmo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwjbyzl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2drjcqphk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2afywxvvw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iarujspk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgbrlj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2apkwwsdn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2eakfsfjn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeapanz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzixvid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2iokqbnxg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gawiowmu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbfgvrv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyhjlkg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2unormsnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnsvrpf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqpepkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuqzire.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiuvlkl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfelzqq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2saoqoerb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtpepkf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxtxaxi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tgegmwyy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvqtivk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbkuczx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eatzoxul.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeuwwmt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlhvqmz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dotrdywo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnosbpmo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndczgxpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgfxef.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2coszhmch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaxying.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irhwroas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxfrjyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwzozwq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfqiyfi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdupswy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gphrlfdy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oveqdtwm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpxofks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiogmxr.html


<!-- 参考信息 -->