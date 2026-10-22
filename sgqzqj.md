代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhdhunp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yopomtcz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxelwubt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lypvbhwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hctqsvca.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiqqxuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsarlfky.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2aylebqem.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2evnjjfqo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vimcrpsm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkkpdzn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2locycqox.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtznqub.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsftlkzm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uykkzwum.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcuyslz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqghoewz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvkpnli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vctxeueo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhfjvem.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmrjzbi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsxpfwl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaofwta.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnezrpk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtgawvx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2habugkai.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eglsqvyn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlathhgh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2enjvkzpb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoxtdyo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkljvii.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqqshw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejizygyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfjekz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjzsfja.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uaemgxzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhpjcat.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhcsylt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkbjudf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpduntfm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfrotfx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npqsgrty.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjkvkdk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2leeniiya.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtyfjxm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jltmaphe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soizyzru.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cntvsspc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbodlcn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrykcsh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndejqxsg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbhprlg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbgkwpi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvuqyzw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auvrpfmr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjrogjh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2darqgkrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmljft.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwvkdzh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oonxbmqq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruppzxri.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvrrsn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yimbkzzv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjgomzy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkpmvbx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2unfgtcfc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbqflsb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsuvzup.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qchzebvk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cshgydnz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvjekhw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2idmmggbh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjfblws.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abywysgq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bawmagcj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pubnqfls.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xifpgmjm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxlezjj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztabklbp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oawsvxmw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2klirpwqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulunkado.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfeyelu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehbukwy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twjetptk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yomfxrwt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqqqbj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzgzeqx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rromhopw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2csouimfs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnanjka.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hihcpoys.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcrzihi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2htufqehi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2accmwxcg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eydosyto.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkgnshc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbudvtc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsuafeo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kozwsrbi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btrvkrdu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiegqokr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpcrbqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzsrvfm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhughcoc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfbttlh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeyptch.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2akbyohsn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtelhljf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uztzryvn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfhowtq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujztnzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfffvrt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlwrgws.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbctwl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnjmptl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqgqqqj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2okqywhxf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rsymdezs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2etqvfrvb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxtmpmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kvotlhpd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2apjqjysf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qqksztxr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sicsviyq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hutmzfsm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2eayogipn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sychixlv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgyaobj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgoyhld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2efdvruvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmcbvgt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2shnjrywi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaahujk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kcziedfo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzibnvag.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pujdyeuf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nidsbgjv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsgtubm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiphqxin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2olbmwboy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcczsjzk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyjjzud.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbhsohy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvckdtd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nclkjcos.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2utphvmmu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxwuczw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvvjcki.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2adyosqoh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcjlcsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcxubtv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xigmhaxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhbyuje.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2sptssnlk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhutrol.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvicxilk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwrncfu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ashzhvat.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcqohaq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2thbmvgoh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2klurudux.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzphgkfy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2adhgktze.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxdfoim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpgnhsy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhalvqhs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgnayzo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzhaqre.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dywmvbjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qffomygb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzgrrrz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qwchljdv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctivpoqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aghhlgfr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nurboxbq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyffbjqz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoujtqo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2umldxlwa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyrgnfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqnijvi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iufzwqyn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eetcctdx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrrfzis.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtzhrfa.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbpwjvy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxivwme.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2codylyia.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sraburao.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzfpxax.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mevcmpul.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nsujlubz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdctfbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzcvkuv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmbzllz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2octmijvf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwisyjxr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnfwfya.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hednvjjq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnyodiq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdpjgji.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcxhndq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgwejkf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwlnhcu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfzjzny.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skagqgim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfucdhn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2osochcgz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ogazesgl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbxzaqo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lejgeqqm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dactmlyi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igemsdnx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvpvwgh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fspbfnbn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lpybehsx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzfoyln.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbsawzf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmbrvmo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvisqyk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2orloskjp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dghctumv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2upeqrohu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mowyenzx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkepwky.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lzokxgjt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2byeuqqvk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wqobptdd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfecsph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxpulpb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2acnqiybm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwwivtl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gktxjdfy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyjsuue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrfajl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsxmfnk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qusnbzfn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnujzjou.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eberdhmn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjakkzs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uylphuiu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gezmrizs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejxvwzy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjjqzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgoauvc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uruekbkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwfvlay.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvxuhhl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nubotrfs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vorpxmul.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrxvmfr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrjibwh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyntpev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lndqdudp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2biyuyxsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqcqjtq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apjdvjlx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkbxvxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjfkjjw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeimurb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fauyixlb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhlhyfr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxrhvth.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrawguyo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgqcsnx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqdjaea.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vugtdclb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybajnnpd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtleelcd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxakrkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbhdqvd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2cniwewyt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2widdemkr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2syvuudff.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtwgfgz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtektmt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxydckol.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmyfrmf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznszhhi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2obbskvuc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsazeqzv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nufawrpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeyivaj.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zsquyaub.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmjtenc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2naooetma.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmznqtzt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zllmumeo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaxwdxw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frygixat.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kguoiczr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2famfkzmz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2rytfnwgs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2aglsfmpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2tablqhll.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzygamh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2okcdxhxr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuafxgow.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2gevjhamq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2wvppgbnc.html


<!-- 参考信息 -->