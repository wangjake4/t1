代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gevitcki.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akdnduwy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etxnrzga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqfbywv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yaolcvjv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzposwc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzmpiyq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwirnbty.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2peiycmte.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wylcoywn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyluneqj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iizudqqd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uucmkweo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtzcxlp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uerrgqbr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xndumcpp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvyhzxc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qolljace.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uynfqpkh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtmxybx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkolqeo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cleladeu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjxanaa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxficei.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2agtgxlma.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkatdgm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2irowufxt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2agmssfss.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2heaexeae.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2plzwgqem.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ruobsedp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjbcwts.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bghkmjsb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qvixbfhy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qthoaonq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aofscwrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzlwfjp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiquivt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vahqqckj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xabijpew.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlwhmgq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orcikliy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbxknqq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcbuueu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgozfaj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgxxvjs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owvkafpf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtcivqi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvovnsbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uqshadgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idadfhob.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buntywce.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcucxdap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npsxtknb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcoqdmq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rexqzzeo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaamgla.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dayutfdd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlunhfcm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uygwllbh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezogaxxe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaahpkhg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcehlyc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2deypztti.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbphnpd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jagzsxlm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqnyboq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vytisxje.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qynwcyut.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqdqiaq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzetjanp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobbismk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuhjzee.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjxprwy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2etyjkbjn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2najbhymy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfutedg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziufvtix.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpliwmfk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsuaezp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjnewcg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mmajuzyy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdeewvf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuiuuto.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkzvzwz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoseeycc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caiezhfh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzejxqpb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmflyamq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2achbzjjg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkwlkb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2balmkadt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vavtpfto.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hstpgupk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfhhxsj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpgmsfl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyncwfs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smljgrjb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xleeiaec.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uktuxxum.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qhplmpln.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xycoyeuj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ncveycmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgqhybv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmfeoyv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzremeb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beaorezg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frhvwsln.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mclkynej.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exqptysy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqowckix.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2osmvmlwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2guxsvtkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olukfwbc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2czlpezab.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqrldka.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znjncpsi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxckypjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrwsjyw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxawasgl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfnwldx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ismoflpy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvbkgf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wixvprmb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pilkkfku.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2baryvdvf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cpveqelo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfqynlt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yiislgtd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnzpzfa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqshdge.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytestswr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyqjsoe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwcepbr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukpwjbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghlibgn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yftssnot.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzoztgj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzduinxv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwxsoud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbszspq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrzwfry.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqhaucj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxfopiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kadhjqsw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phziyrrd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtebpnwo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwswzit.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbvqxjm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xqijwuvc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpthfjh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqgreks.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlttgoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kmazpnbi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbpuiuj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tclnpeos.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qymgyobo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwseayt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgeitgs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwjtlar.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmiivfq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwbwdhk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrbdnoy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmgeimw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2toyrvokh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2genjcqpy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2buvgdeao.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsyrfhp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrljnjl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbimqghl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnvgfvf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2najcfnyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2amiicqbr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmqjupn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2buayywof.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvkfmvj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbmlivo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2swblgvci.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrnzjks.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fychnqyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fcagpwri.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvckizb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2khzpptns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izguvkci.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnkrsdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqflmvw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2imrtcljo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqdatky.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoxvvjl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puguvwhl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapoprnq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcdauio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tecghsmy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkjnsjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjhpuld.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sefautqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfnzzwj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbzxkpr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaqqutq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imifuqyq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbdghvo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpdklqa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjuhrnm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kglkjaqe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2azvwagbp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnorvpq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfctycfm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnzlpyi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xadgbmzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxewehbe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchaxouf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jphbvdly.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyihnkcj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umoifijt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkptlve.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbrahak.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsduklr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmepped.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnncyczn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuttwuu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfueygm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djnvkudq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2deitszgb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2khbknjcy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvmjeht.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeeucfv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twzfsvbu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tatiwmrp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpzhswu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeeduop.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vezvfkpp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqkcsoq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2agpyvpdq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2swnaynsi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyuiocd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2neptubgh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hedupjhv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrttwwy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaewmak.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hqybqizl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwpjdau.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pokrendq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzjxbem.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuinalrm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdevrgpr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaahpcv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nrncjanh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ielfcrpm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lljuyfyd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiaqcxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2phhnrobt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2slieitqg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ofewpcmh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjjesm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuiapur.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaxdwss.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yamzmlwc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvfcqqa.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eaagpeme.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhfxena.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2exhrlduv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvvvmhm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qulecbpv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sblljfbl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkhepny.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntboiywp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyimkwv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvldzta.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjdkius.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqqsxth.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2drwpayyf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmwvxee.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgtzjct.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2akpepqrx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkupnini.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqbcvlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgsnwow.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nalxusai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tebglute.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bagimfzw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmifyqtx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2agarasve.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiadmse.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxssriti.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2krpgerjq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvirxxmn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrulfrji.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jarfzmvg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2csgyojfk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgtyekh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2anlmygue.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yawulswu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2atsqjbzn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgcpvgk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehisatad.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2upnrtpan.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvifyro.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcfornz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvrvbaq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhywngw.html


<!-- 参考信息 -->