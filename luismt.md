代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rmixvzrx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2raatcjga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nifwbvwk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcnoxfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzbevbn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljhjwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxezev.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqccews.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlkjfue.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvppwjxc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vznwhqqw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfuxuzn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhrfkdw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvhecbf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvurmlld.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqgrscn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fckjmvic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbtycya.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sntngxax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tewigfzh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwkmugn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waticdtz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sniuyspj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjqlgkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmkzws.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrcunbc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yokcoiab.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgpwfbv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhtspjk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlruoebd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bccavfuk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yoamniud.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gieuabez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwlylfn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hablubed.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbghpzf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzvlvpo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvktnaiu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cartitmg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnkttmw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdknfwbc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfsaeej.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sooobpju.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrunnqo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2abcvsmlt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewodftwp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezetcoch.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzhgpls.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oidlvyzf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tgucxlgj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qswsgsci.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqefukes.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqumjaln.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxexbbb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uepsnrsj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifqsdsc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnxtmlb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeksztd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtjrvxf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxbgdn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2usutdjet.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmurvvdk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqxqjtq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbostzd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuwphjr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrthruo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2suctvxuu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2acjxhqyl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmrlwku.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ociaysqu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ratdxfhe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqnojzn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagewaj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odssvdws.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opwqlijc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aziitzbi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcgicpx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2juntqdix.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqtjfxw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmarbedi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hngxnefp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tckoxspi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxuvudx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unyzoncq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wckmicns.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkgaekf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnczjdfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfukztst.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wudziruq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjkqzve.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dejslaql.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2stnkldic.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdheeeh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dhldqpqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hglyspsu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qevvpsyg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnbiwrb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ookvcbkk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbfjdbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnshxsva.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyhfdsg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqnzrbj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqorzumw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooosdjhg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmvtbmw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duvzpxis.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmvxpjl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhgulqp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxeunhb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgvbobu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipatjlel.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zakfpqzr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdqptur.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqctughl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbbntxo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orbqnzst.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qroraskh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdefyfjn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pyadlhox.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqachsp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgnisrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nowlkrdz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqrtzkh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qullkvxz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2emqsicrq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wtawwfds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrfpcmz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2llwfumvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsazysca.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhnautw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnlqypc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmntwzj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfohhwsx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcpiwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxfzrmh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpxyjsc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthlgxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ditqylbk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2asbarxht.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwtifsp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nibqrjxt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmgktqv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmomfac.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bncjcakm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tafvzxyl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqjxeln.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jasfpegz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wapnknlv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rtubxinr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfcgzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qutrbtxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owezysja.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxspyng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwzrnmv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kzegpwvy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcewkc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljmkict.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoruwvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfalcgfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbwqesx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbhmskx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkqigmt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvshgxbk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2njxzszcf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaatqum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsitxsqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxujfab.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giayjxof.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2caocugsz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmglbst.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyvjodz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbiknmv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgrpbie.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhwcamg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezezxrdc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjhlmv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2quezicvx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgusdxz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvuazgk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydengfhc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxbshoo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eudwatgt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vphtljig.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cborzmwg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qklukqsp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxkltdd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2armnzfxi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjiwrjs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bikirnph.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgsozdk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgsfxwg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2khwtvnkp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbbhpgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tddcixsf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpjuiix.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grbbmqip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemjugho.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2aeabtcnb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clozgbiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyaklay.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hrivtkxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvdpoqk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzgkejn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2worlvjsp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqpwczi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mobohwkz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmltdvi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2quiadpom.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnvkkx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xunpcjur.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tezoeerk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvkzffi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukxzigl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhmmdnx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oypathjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxrcoie.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlvphjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnzhxkd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2frdgxezn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnvbytl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgpdfof.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbinctdm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2figgkwsn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxxxmg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfwklrm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmzcvnl.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onbdmhyp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtiiagm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaaznqf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2idnmgxwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkuycup.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlcbrn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ievhvhdr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgtkogq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsfvlpa.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxonbxs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwuwtlk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2eritrvqv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2acdtrdug.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzhfwbc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zerymfrx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2edpcsoep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehptsbus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sntpqmad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssesrprn.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvimprjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvozcgq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkrjyrb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htyqjzbm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvkmoha.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcoqaft.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgajbbm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeeygnn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dygqqjqr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2unumbxtc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2irsdvuxh.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djzrmrlt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxzagck.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsplkoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzlenay.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2htzsdcvl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgxgjlw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvbwfry.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmnuqou.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nethfgwz.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiaqwgz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmghnnae.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qoewqvhf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyoivdp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wutxfkob.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjvfsj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoodwik.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqexdcpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsdfbjf.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrcuciq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wionlwsd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qncdobkk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkmwbqz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmitwlv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzaetfa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqourctw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2awqqzbcp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sketjabc.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nadlibbp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmmmjag.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vniojqhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhdsmbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2awinmtzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2txrblctq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrfjzfd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqshxsy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfovmdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyffkxg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gksxzljm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2eomlqlkl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2smtqlupk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2tneqwrvh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhicnpe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxlowzm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2njvivrqf.html


<!-- 参考信息 -->