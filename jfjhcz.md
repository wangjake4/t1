代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rxflwgby.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2knvkkgmw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxehqzi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2slshifqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aigeltth.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxcmug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzwxfql.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zikvucve.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbaehqf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyrnabc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neteeavf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgxfykg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axepllbw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2utyjgwux.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmbevft.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmegzcx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glpcenef.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzukfwhq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnrhyih.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmayicz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwediwjd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qecxefko.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapaqkev.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmpbscu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjjijoc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2btbrgxlf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkseyzsb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgiwess.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rixgdoff.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqkdien.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmxfmwn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszyblz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2htmcdkth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdumprj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfwbuvj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iopescdy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keetmumg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbawceq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopcfywj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyiroce.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2blvzkdlm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kibruxbd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vazqplye.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhytqbu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlnwntu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzbklhx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsrhfzl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwlasjq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhuvvhw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kxombkpr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2okrqyzwc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glrlkpwy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrkmwjd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwejwwg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzgaqgb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpwlrll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpfctxw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsbeptd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvkrthh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khyumvlm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbwctkf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezikdrsi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dueahstp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2azhgqtkl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhxmzzk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2feeuremg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ildtseio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcgjhx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkhngoi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivynqnwy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgjjduh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtlogq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnqrqmy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwnegpy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggshzvpx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjmywia.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xpghuekw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bndfcaqu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rojmhlii.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvacmke.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzymvmy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fasolfgw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vutitppz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdygdtm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brszoeas.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfcchqy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjaxyqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgjiias.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2obqhaojy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tywnevfx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wcywfvqx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzpkdrm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhrwlnu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdqrfux.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eehwfckj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuuggen.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqudqrl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsouqbv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2twkeudhu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplqpwfo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwonabit.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhudlfpp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbqgeip.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumzodou.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzuwuyi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsnegtz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zeglrwyk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2crectomm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkgnjxh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scxkmbqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrnfheu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usyiybsg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbkfxmu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyaimsg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xechmafp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rflxivke.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsmioqe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzfosan.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbgstir.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2adummypw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knyypqxj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xbupajga.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojedgie.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yubzsdrg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2onpgvhgg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2elmhqqrl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rznypeon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aklyhzej.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnjnate.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdjyrci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpukyxvh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsnvaew.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrkrwdz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nbowbzic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqcjqcj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvbszqm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jugoxefw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdqscta.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjueenx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfuzsja.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2eypbsuye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2petxvwjq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2paprbyas.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kllcycss.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nccidcri.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqixdoqh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eormuwnk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcjynhp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeutdeg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2riicfqfs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtayltg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhazazid.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2boadhuuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znpajyzx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iuukatzq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzygtjh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpmejhr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzacmady.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgwznv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spjqjfle.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbjqbra.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2parucwbf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyuyajj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiimnfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfipucf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaohfewt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmibcztx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etxppiro.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvbfccr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xrapclti.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfsrfdb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkiacqe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2phdwvcff.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfyzrtu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwarjtw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pauiqrls.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbddapon.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2janmpnpn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2prdcrxzd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqifvled.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhwlboz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwjfgqu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaimkio.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2punfkxej.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzyiphi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjigrqwc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nstjhcwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyrnesn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvimdp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnguvei.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqxaohi.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmxeamz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrzbtwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nywjgzsx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qizdikmk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utzuhkpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwoxud.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qubcalcy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fanuzdjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrpcmza.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsbobjm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2klrxpchv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorremq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkgtkvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2faikkobf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftsmtd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jelzeoqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbnqiex.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwcvoc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclgghf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2whzuyyar.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgrmft.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2awdzgvfy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqncodz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2soivpktg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgeqiqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhfewek.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgjuojj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmunhap.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vimbffik.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pywfwehz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfevosay.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvearkzn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsfdryn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2drvqexro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsqggoh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pvieklgp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2skdtsxvn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbyjkkz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpujamnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrpeemt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlxcmpc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2irmfydvw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2trsrlohy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2khrfaewy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhjngbb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qanwbnxu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvizzqev.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2egjuoddt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bebsbhry.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2amuvjorz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2aapjqilg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gairbizy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxwgjms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuksgge.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwwtajl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xksxhagf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzinvrx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2httmkobe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqtuqkc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibhkhoz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlixlpm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbnuovs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhxcyzn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtdxahl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhuextu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbqhfvr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsifnpp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlgdgis.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmajoecs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimtutdq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjvltwu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjykzkl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuuzmzv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqdlfnn.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxrfbrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipdexem.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldoztg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmlpgnv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zigbpfjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfajiguv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqhbqym.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2chleavmv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2bxttsuph.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gayxciaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxwfeap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmslnby.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qledfgjk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2agrqfjqo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dythjplp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnqkgmn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pksrqkjp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxmsxpq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhpobog.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxvtnta.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2omjcpzly.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozjqrqs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnpfjpj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxidpftq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxbbyjz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmwrddf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdbvkip.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpypriew.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjvjbhc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpwgand.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2oznfgoad.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvbgvvx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuicqoql.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbccdqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjuqsdd.html


<!-- 参考信息 -->