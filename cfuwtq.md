代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2adzaorlo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqgklxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqulzst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxowlpb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgfnwzb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwgzxpb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbizdgrl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dskstilg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kovznsdi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gusuevrh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoznltyy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcjbnoc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwbpuvm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dilwoein.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooftricb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxdrorv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbccycw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfelqqqd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpaubc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkudsrw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xifzfnyt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbdhxhl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mflavcaz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rynczjlm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoyzzuh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xsncvihm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wagmiplp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yrokoewm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwycypr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlisrym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqxsdqx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttdbul.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2skiicqlv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdupkzs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrkcvwr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmojbko.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvcifxk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2inbcmvsn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwljuinh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfpbeg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhebwzer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrpytqf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuugujl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrglrqyp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uglhmfqg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoitjbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aarpharg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kreiadgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afnpezmy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2reyrsmhe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibihzbjz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lufgmxcq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvamecu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxixocnj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdgdqef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmhwvjb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yklzqfnr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcicesk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glqgmokg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhcrfmj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqrkmjl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpcxixr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkjaoda.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlohfxxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iudgsjaq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkyuuw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eelnklch.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2okzsxvth.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nknxshfq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sciayhsi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aieegmog.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkeiymk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbupqx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwzawsd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqychcb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fndyjrox.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyepcmc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoflipz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmulzaxs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotvhnk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upberxsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootjswwx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2blwnokzl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhtgpci.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoleqzk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzycfzm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcepuqn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bompiqwr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpepbrus.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmrvslg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdubtxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvskcuc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmndqbq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjafmkpf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ebljamuu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2twtdmlox.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgztoblj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kibyhvgw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhecbzl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vybvfqov.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkqaszv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtvczfq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcvgpux.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhdoxgw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ndppqreu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrivlyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gatusxhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzwlvet.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwvcvgj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgbyyvi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmfyvgj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eirgbkii.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbvqdxn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lycbczyj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcnxapi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrzmjcx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsxlkuu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeeolyq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfjiohr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjfgaow.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdnqvrq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwzccbp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkilvnn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cneypajg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcpjdqo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmylbsq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfadttyk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsbyphc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnhfkai.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arlkppmo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaswkcd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sngmlmtn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pamcxgnb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidchex.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tblhdhhi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siyblbfx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmknafat.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cipcycrd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxpueyi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qyohibuf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmccwr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiszdrv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjmmhah.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ashzzpjo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zottubpl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tndbzunp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojhcrdv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tohfhuhy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttmmrt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyeelho.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmexljk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhldjpr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpedvuhe.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aprnywgm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2myycyrqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvumgko.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjncyvc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoopytk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfjnbnu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icpixngn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fsczhsll.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpshmjea.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgntwbu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbwxypx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkrgzus.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cistuchu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoyytxt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iljfxvkk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdwgdwx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyniojgq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2waffqfmq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsahyvah.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eawbuihq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ujifvsmo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnqkxgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tapzewmh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdsynyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otxzbvtl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmwpduj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrtywnk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtirlpk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tevblfcw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqynrkqt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsbquvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrvjdku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2binlelxb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfpptdf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxushvj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwnlgy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhojjfl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqehtwox.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqjppag.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duuwdytb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqsuxkm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jowyndhr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvxcneg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvvaevd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjcrvnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2svvozcjt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcgxsq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jerlglht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2grnnqmrf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2slsslotz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjfotom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gztwhrmd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hefefwkf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhdqqba.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfsgqpq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hffoeajq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awmrvwfz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzuzsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmduczyc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfoumiw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uayifkyf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpotmpar.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvwrjdz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mielnjqw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdovaddg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxmybak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otjmyofz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2htlnirvd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mosqgooc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uipvmrve.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vxutywrj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjofprd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2myllvqwu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ionslvbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxmtnj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdeotsi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhutxos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrccomxc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lrztqdtj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkekrid.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxujwjj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2atstfaim.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztazucm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqduvnc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoeewul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjtfcyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhpzkgp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyibekl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rczgldgn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrtgobi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjtxrwb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rremltws.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrshpxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2arpyqrqd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tissczlm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbmlfnw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnytbzo.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2asajcxzn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2iurkxsgg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pquhwytd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnpqzoh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xngvxrtk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ritoyjuw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qyacrypx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngamsoxq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoajmas.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zuystevd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhbikur.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhqwrt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ajngqaya.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhryhdu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkncnyd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrefzhn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlbobkv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyzbjrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exsjnsqg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hceyeier.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lderrggg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjmkzva.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inkhpyst.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqoebgl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhneifwm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabwxlmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cccgguep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jraxhkoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxhinav.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxwjnep.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2goowzlvs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcvvggv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaoqqdr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qiesiwvd.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyjodpm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqatmt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aicogahm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2orqtvnyd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nixgschg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rghfdovc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbygemz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ftidfydn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeloufc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkodljxi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfajdrgl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmxifkq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtsjfqp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqpvcr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bysdbusa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2npipdvka.html


<!-- 参考信息 -->