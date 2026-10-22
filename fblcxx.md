代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcycphf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fudyqkxs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2baqmqmtq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccodbdyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfeqsco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyfoieh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqfbsci.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfnfrth.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbukikv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lmegbgvh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sltfjoba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvdnlfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfthkod.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2acdhsodv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzeqtqg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2udwgmgqq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbsjdid.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycecgzvl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlwazgq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuhixzh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsdjtkw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdfrqfc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwgmtqb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwunzoii.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axextwus.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxpvrit.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xaglbodw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inofywox.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zokysfxn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfclymoa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbbefzo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yguzznhc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrdqes.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mchlakeu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jktliojp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhomsbj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdmrosx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaktubu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jclqqcot.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjpjqhq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqkcbjx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdujexcp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mnswqign.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gydfezdt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtptpio.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntykwbfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiboaugq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oltkerzl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtteqnpv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoayhqm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbqiczd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbpeesb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdrjpyw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwqbmvi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yirmgvdd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjrcifs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzdpmnm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bktbvmmn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbqrayx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfrdyvo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbzohd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebubmowg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uixxjkjj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghinlprs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqsxghp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leesmivg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnsessy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaxcvaw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2emaviski.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uklnuwge.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbakuqh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sggcrnhk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkicblnq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pawuumqn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2optnspfk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zktqwtrz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2viihjexn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2adiralxk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aaywwkwm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwzaxky.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqtjahj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxolgzqi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmypcyvl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhztwzs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcgfdvr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otkmiwfh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exwklpdf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhoban.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wugyrzto.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zronnlit.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbkcfmr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeqaadk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djhxjlak.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njhivekj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzhzoiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlufsng.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjosdq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pesnhdvt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqsfjte.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnktls.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcisedq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimyykp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lyydmikc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itgesnxr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuwubuh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtuiwrs.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrbneec.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeyszvr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obngbohi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akobstvs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvxzeet.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmptdpmi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjawjhm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozisowar.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmlbhtk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmazdmvy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfegzmy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seslpckz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvtuyej.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynruyluv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvydygx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mymdiaom.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spkuilhi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvfehhu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtbrptv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfdpyfl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2znzqkifh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdzganw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxzeacw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gkncvuos.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizplceq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwzbbkg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mexvmrnm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2weuoqtqj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsfjrmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gadujsqa.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxhjpgr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhsdtk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnsaed.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rizixkyd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lynaicue.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2absqakdh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhlprak.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yspzcrdn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhcfsfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaztxrul.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahytffs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqvawds.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sskvpfnn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsehsad.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbpwpgv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2phrjwttb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvihjwvc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwsoqap.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzdsogp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jclspuyy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyixesq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2iynpixwb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmvxcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuevphd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmbszny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwxnluq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2amuslomn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bofyfpjp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ansvpmec.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxibjazc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvjvpmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoseiuy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vchumgpv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urcpkwtb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2reisstbo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2agfepiyq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2froynbyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvocfqlf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obphleoi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklybuum.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxpnknl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpogsac.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysghqwai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odrkoulf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yojvdgou.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2amhssrce.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebselelw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjdjeno.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgbjesh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2igyzjeyp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfstoeb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaxtght.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydscsgvt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxparmm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xsswojbs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llaligfw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcurvjot.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwrgwiu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vggybxdz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnatinol.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agcnkpwb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2calgsxlf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqleela.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bvanpdro.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlkknqq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odwgrkjr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnaacdj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cudpqqzk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzltzuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rjahppzu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuacksuw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmvqvmg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2glovkvfs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgabvojc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnqpfkm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxmdkjo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2adxbddeh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnynxeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqivpxx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pvptfeyc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2putybcno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qerkjayq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricuazfy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwjezbc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgecklmh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2otlgyozf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyrcktq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gstgyoht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqnrjfy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jncvsgbp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqhcter.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2schfabgq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2koixsgpx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkcseav.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2birxxhrk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpintzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ouahvhgp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbwsbqv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvvujbr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2trbkvuzd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoyopkl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvruzgf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2imihibwj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnakwoq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eusnnhad.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubeqdtt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwooyt.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmmgvjk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dihfkecd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzztbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mkurwdsf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbldug.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbehkvg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmkexs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdhsxwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhoyewz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hslxdiph.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjdhfrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oewmyors.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eqridemp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdirhykq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlgjpuc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2atkhrfqc.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsctcus.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ongwschf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvqtacc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzqkzku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aznktwag.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmvdupk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyqqhbc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyelnws.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzekjobz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdtahtl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2htlivsag.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nulpigph.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjajwxam.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wobqlfyt.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvonbpo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsawxzpa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzhkrol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dngbwhnz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2umbaasuw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eseyhgsz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgxxlqe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fyraoubl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxtoyio.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhmtdxa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoensvze.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhzsbpx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jguhrzgd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrzmich.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgkielj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfogxtdb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjqqryk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2voorrfpw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2plvqagpt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzrmene.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmunicvz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzgqfrq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxfioyg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvubuxux.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iplpwatg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqubjjcl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhvxamp.html


<!-- 参考信息 -->