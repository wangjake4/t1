代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgpmqhg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwssnca.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvjfjhq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tokmstyn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlpogsx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uremkwoz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqmksrz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2izyqbkpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jswvlmfo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwnoia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clpwwhjk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2slskpiuu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lvapddke.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfkgeha.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaevtab.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkjryzz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjgfnil.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfinogbl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djlwxvzp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwmnnc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfvbsis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2veeuhqhx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bphqmtxd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyaspsn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnpodgt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfnnkpt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmmlfnx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nozrczbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtvnmdt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvxyyam.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wejuvoln.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpercxa.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oomznsnu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2klqfmvcd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iijkgqqh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2znxwalbi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcbnkap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twjeszja.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtzohpl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsgaikm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbizpiu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcntonr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxrtckq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhocjiv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnogardh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xiswexxo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgavairq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmulrws.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2djcxbkoi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upyhvftf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqlhdag.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxguxxb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siyjaxbx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlwbzqg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwteugnq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uabyohpc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dufdwtig.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmjdrcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvtzzhg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxbnxh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkffnorx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdmjajr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjczcvl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnefnkkh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2acbwbotm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzohteia.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjurflq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqelhtg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqscazq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2snbubyxk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gegrvspt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odjvjaom.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2usvlfsdi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2egkaimgw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vuanykxq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhzfxn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzusxnne.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxfhqsb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoenfrie.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkenvvy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwospup.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgivdkry.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeujdxts.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwvoswd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjrdghh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hojnpabv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjzqyum.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epwyrakm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxrzxai.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcdcmjc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nctsyzqg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufislhdt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gsssvesv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryovnpvu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcbqcvg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rulcyvlk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrhrbiw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cecymtmd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxdybmd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yafbhypa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2toocdcya.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uvionecu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmdmcxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjdochx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwcqawi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtphjxl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itvcljpt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgncmpp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wldaaxqg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukxjgbt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdxwmov.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2geubvful.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxaqshe.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnuhica.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbricrd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdgzqqe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpetzj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qypzxkwh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvsswmg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqczolg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrqiips.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rsejfncg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owlzrusl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zawughmh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtrnbbl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xskstten.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfhqltk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sudxdklh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hujdhpwu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpkxgnj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwubpul.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkjrtwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdnrcet.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdksweo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2welvdlbn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqehxyy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdhkkvj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvfvhbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqauyty.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatwoagl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2voooqprc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmlzrdw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2swymeeoc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmlkdy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtgetme.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnfcaim.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2htbvhzxe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nxafkejw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxwalrl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oopbwjcv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxiltwg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjahuipj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2liyqhbjx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjwmusw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvknogc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nshdopjo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jczzixhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvrfsrh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fdetadzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsczoyp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeprzmyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdpwlhk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxcput.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungiafyp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ehapagaz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzexyox.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvywqfk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqczwyx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaepyni.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqacaeh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobivnq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqhsyoa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnjcxfi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfmibuq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wevmqgee.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijzznng.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acykstlm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjkisuh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfgjnde.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2clvultrr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzxmsok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gifmnayi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvurfyra.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2turwfggs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sygcscpd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eeouaouo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2suaymjgx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvatgqs.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krtukmte.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfluesy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjombxz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbbfgvo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnioids.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvrgnbx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhstjfob.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwlddve.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpjcziw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhghlqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxzfbyd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iprudjnf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpbztsz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yedbpvhi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkevfqtz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkmdlww.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkdyavf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbynwgj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfeijhl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oozbmwwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxjresb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2busqjfqg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqrexgu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmlpziy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2geaufyfm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfagvua.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrylwlzo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykchkcra.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfheqsu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpbbfvi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfwwwci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqxceen.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbbldmw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajzyup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclvqrz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpxmsaq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2hedyetgp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwbyfud.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqlnilh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaorvof.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2frknpcpd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nvonlyul.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdgiqdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsosvgk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsuovhg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsmfkip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchbnghl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjnvdjb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxdwlwx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2evoboarw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiydkpt.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaadteb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wczqviqi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2hphosgnt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlrsqhz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqaevxf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwsxpxn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjfcnn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecamuovj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiqxflf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrfrxbj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmdkgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcwaiu.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imsigjtk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urewenyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubymzyca.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zelyodnz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2clphyxmo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjeteec.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftebjzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusaylmd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbfmqlv.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2misglcif.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orhrtvxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfplmiin.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwpfyeo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvoxxjb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juopejqf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntbotuw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpgewqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbxcxdi.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrwxwzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeemxau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ageaelbi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnqjtyj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2utftvree.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrlepwt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhgasiq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2palolwkj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzoycha.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcmfmcc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wctczvpj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dutxasxf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2egjlsjiy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqbqbjt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdnlocn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2exhzzlrp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmtpznb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2snejijzg.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuaflph.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbmiwwe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmhezvm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvyullm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjixvsij.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2khiriuau.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrkdvkr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jonvihwk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxmdixz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfdllnk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2afqurpio.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2eptgynhg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoogdww.html


<!-- 参考信息 -->