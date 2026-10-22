代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxcwmf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyjwdxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xosbdwgi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irlqxugb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ownfoisf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrdrfgx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbkazlm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeoawda.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpewedyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiriicr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgttjwr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hncsugsi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqywlv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afmjjjkk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupkcdql.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnkhnir.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2obclbhwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtinuco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdximha.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kodtzdzp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bjulcgmx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jzusjwio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2izxdjoqo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjgkiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzvmjlb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxupqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twsydpmq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vygbmvxt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqxtqlf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njkywxxl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kukprzjo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwzkrth.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxicqvw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtiqgyw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvslufoz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvkdzaq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btfertlg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sryukzgn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjjscso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyqaxra.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byoevstp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccruwyxp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2strqhwos.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2koeopfcn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfonyegd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jbviuygx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rimyrygs.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwthlbs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yofwdkph.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybizghwc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjvpmqn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhcnqnj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyljeci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfroszwc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cizkcbkj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kzehnlrn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyaadgh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dapdsbww.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyidfsft.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nejysngu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zohngoyn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjpciuj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuytulkk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrowiox.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2khoiswsf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2appyyjma.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpekjktg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pciaqzvz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2memcfsff.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2szmklkna.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpglokzt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2extuchxh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yinhsubv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoczjhm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafoynkr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyleytj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rofiqhhi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbmqkir.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2neqkzrvy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqhqzwl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtdxdbr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gcayejpb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2faxpsrar.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nixesiiz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymwqrd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxojuue.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpurbfc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfdlpww.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cquptqtg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzrydmi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vfleuryz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcfuivy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgeieuq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpldknxk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oknibylr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2finytkxn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2buffefhg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldegagye.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhukhfr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2moobmtjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdhtobe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuwqjaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2idwhhngd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvoucum.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjpuscv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlobesfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnphzz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyofufgs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhiuzo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qitvmocq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdubwyh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lldnaeli.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kfarhfpi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xzftulox.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrctxnf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvbncpv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgfetjq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxtwxnn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sloklzdp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnacwnn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfiakwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxglmfqe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnatdzm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2txcausjd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmhfpkf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaimgwz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxkffcl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2grstbfln.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrladzxx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myeqisba.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrkyvkd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erwwulxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2giktlzsy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzazppl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsksfwsr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2juotmltk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbmvpfi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfzqdnb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkxemjx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2foufphie.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jtznotss.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tiohrqdt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwihfnwh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mshgmjxk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqbwhwm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuvgspw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdkshil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdxnuot.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oolzjaji.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxchhrjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqdllfw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gcypjara.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqtfieq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyimfbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dohmfqfz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzvmiu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaruwot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdaugpd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdteout.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2krpezwfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2upofbeiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpubmzo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mstokhny.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uirgujom.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyjvsjt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqhijga.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2paduljjt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciserkib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pklfuuby.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2axvgapmq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmffrjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqyrhen.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzmwamw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cahqbcgp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nytjhnst.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2woaehcwm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mntwjuxu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qspornsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbravlhu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjmwhe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2paenlhnx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aytexofb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpaumfs.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkwpdwj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcoorft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbauqpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiklzeqf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyuhvph.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjizxkn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzonhoea.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvquikrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqruciy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeglinh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsknfvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdribwhx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjwymue.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsomlqwb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tckimqiy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2svnnbjkj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzomsepr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mablbchf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfuvddp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cllugprc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhytqzsb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cetwfbba.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrgsqhh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2welzohwi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkeqfbj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqzdrw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toszyyrj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpdpqzl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhfbylg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njvlynyg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqtwkme.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjydwban.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzomvbtt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjyvjvn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjpazfc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pspugahe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtgtyns.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyvkajz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywdreqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxffprj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sdakafym.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhylyp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2honhdkus.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddomeqk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vckqueln.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjqcuc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnezjsw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xszitdcr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zreorejs.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxqwly.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2luaxaapm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2marrbaih.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoyylxv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcobysmn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2prljscmr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssacluyj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyrawpi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pegapezp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufgzynp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnnxgke.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2exdqxnyk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdemram.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsddklw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyvurny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2giautwkq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvysbgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2islramze.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyygjuqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwnmovv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqyafpu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswewhua.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqpyycb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jypynbfp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2juurwobo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxebmmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eojomueq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2knxrhazy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nisdfhfz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoqhsmv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bucfrjho.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuavvmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yclhxsye.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlsweoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiblpwix.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvjggeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjhftja.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfdrzkt.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnlqsvn.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrhcaio.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdpqdgx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvuohvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpiklxy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqnkee.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpfhwxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwqpnc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2prwyukpe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzmnowd.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tizchqjc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlapawvm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrtiguc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2haziqswx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuhcjjr.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2himpqlfm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwsgyal.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmufstmq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sptaaame.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmbkasa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqiqxrm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsnalpi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrgvpf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrrozn.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uodilvoe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivmiwhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwklvez.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzpowym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnawtsky.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sncjhagf.html


<!-- 参考信息 -->