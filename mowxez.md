代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeszmmi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rlskhlcw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lorbrrey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyshuiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lllnaibf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2enunubcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpcvvyq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qirggtgl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlgamcv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaotwji.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnayqwc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2najkdogs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cglgqysd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlqovio.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzjqxts.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoagbuh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzyztbw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2csxtbhqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpibwedr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qooooimh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdvjdhf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxyfcbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hldexpjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebajggdh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heysqqav.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2idqtnfai.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2odvsgrrj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexwnnu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtixreb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkvadjo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pimzcjgd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdfrwxv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyfofef.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjurrgqo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gloamzjx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ixquqmlt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyuhvdl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcacruy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqkdyzf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cebcttxe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgsbrpl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjsqsxb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasptztx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqpxwae.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eofwcfwv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmkuejm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmccdfce.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqsovca.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iallobbc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lscbbbtb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nibyxlyn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knrmqzdp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vasxiadw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlqmivt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswcsseh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntparrhl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcslcsq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyhoslv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzctmyb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjycoea.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqquaoo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgvqwc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmvklwz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwyvbmk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2usscspfc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwwnwe.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2isuratxr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeqjaod.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2efaaacwv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phqsidvg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cydjzbkt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2utsxdmot.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fituoagy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbbcsc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owoaerxv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgratoij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2steyfcyt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bapxahtr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqphrsdm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzhtohs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xujttysk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsgghub.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbgwyup.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2craanlgx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdpjpad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkmpjyy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asmlkdbs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhppxhrt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyosjab.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bavxsfgh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eagzyfln.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lgirzute.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbxklju.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eauxoesf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fycginqv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwixlws.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2exwalzho.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iebhveay.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ceddnwxd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqrusag.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfymkjcu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyioqit.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njrimvbg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2egcfrosh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvougm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittjbpqi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkltpnu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cekiotxm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaiwrci.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwliyhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvcqyme.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phbwjohi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnymvup.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjkrirp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2merjmjhr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjztwsnf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvzqjml.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kkikrrmh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqlqpzl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxhmunm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgvhbyc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrkyzhh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxaipz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqrpcyg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bwddjvfi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpahzpo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfkblzj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhplgjf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpbrrvn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aesoxbyn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmtgjun.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjekerq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgechrza.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbjgskl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavhrrg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxusify.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlujglv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznlevnz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbcbjcd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafydljc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzwlmcf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pldzeccu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzrprab.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftkpeu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtriahio.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2johoevmq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezedyhs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfonfiit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2riierayc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjesxho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2efkfjocl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrydytl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwmyzvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzmrnox.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2filbtyyk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mczubdmt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxdpyi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjupeg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oltkztfp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvdsqst.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuemkdm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmbhifo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxdwrw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jlimmbdn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdwdima.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sybvvzbt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugvtiob.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsvnqe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plltlxpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpdnoca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgtldnv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsenrlu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdzefoi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cadmceex.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgzllgm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuscmkb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tveeweza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhujrtq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeonydma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2umutindf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gequoxxd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdhwlpv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdwsttb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgklycdx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upwuqxfc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mogheqhi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uapxrnex.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yemcgawm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hougvbqh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cttajwnh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aystumst.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcagbim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwebisz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmfxwvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wncehwif.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrochdcb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxgjzun.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2icadgnxs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnapjfhm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vdthypdy.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpdhww.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiaedkw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rnllweft.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iekadxhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2oczyukqy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyyyjst.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yssfwfnp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mifxxmfs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cpotburh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sticsdaf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vapirfyq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eepkyzpo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oioaozvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2deczruly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbqfbvt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbnrdcj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyuwkmy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjtzqub.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrltwxrk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yoornogt.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2orcychts.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvngyay.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvizvdt.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iybradbp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fanlgndf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtkqntk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfvxply.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gamkdnwb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpixxnb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwmrcti.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjwfhnv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmzpdoh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cchjrwhs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2infkpnyu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbrvumg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhedbkr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2grsvpiel.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vthprqcn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlumren.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bhntywcw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuoegrn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmwihgk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzmzryg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmnicmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sckhdyyq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfchxrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkbzvwg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgatajh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhkpalu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2toveywng.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfvlmsg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwdzquv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuxczum.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpevfov.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzydwga.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztxwjg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxkwdcy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyndypkd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpgdmz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2udwdrspi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnwpqhm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaepgwyg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atyjylyk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sycgssqr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kasncomx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2factuhmj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsofihc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrbvouo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2machvtei.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cghbtqon.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2czslqurn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2eiklehzj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2csoqjeth.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpuagtm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdjohcp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhbnsw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfmmbxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2asidjoek.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjaqzuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsdegkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwkalfi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2afgwgqap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvifngi.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxzitei.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsquwqis.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jydqdoeo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxckntt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeotcsii.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwktbatf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrxzwfj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgagubm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpjara.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtrnepz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zorezbud.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjyytku.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwngdgp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgsrmff.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqcplzt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2mliwmoxg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiwbofu.html


<!-- 参考信息 -->