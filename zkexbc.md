代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtmaoea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjnckkj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhxoxxe.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmblqo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bzayonqt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaieiej.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jinaaxlx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jaheckqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbstdqr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgmfxvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oukurynr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpxscqh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qxstjdtg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkngre.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evxtirft.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqmtsr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cedlfbox.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xikqzagg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsktora.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrieuctd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aykgjxfg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhysrww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slykzdjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cahrodym.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ungjietc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqbkeio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkskrqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bytcchkn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyadixrc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfyrvxj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcieypl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkxyhpj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2thvfyrwb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvignii.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxihbksx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxalybs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfbjlzx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tagscpnw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqagegr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqgazsq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotzqmas.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gigodagy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcpxcdh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvczbwbx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvutsxep.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctunaokd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jauffnoj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2humlqedk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtpfjvw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2javkdkjc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khnsiahu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whermbsf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnkjvwo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcrhnbn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlhgyjb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woyaswuu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfeweea.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tegyrrrh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcvobon.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csxspime.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdflztm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxehnceo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpnmtjh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzdxfxo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfaxfsy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cthvbtjo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2acotfrga.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkgnbdb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tciyewwf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkldjiti.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhlwmzy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubspdwon.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyofxhg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2masoidzq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mgukrhgz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uopygrwj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ritxrhhs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjicjfv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaccpuh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egbsnjar.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpifpyp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwojxjw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvylqnxt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxcwmtt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iglzhknm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyxquyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fqepbbng.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbsltid.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piruyaew.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyvueao.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcggked.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwasdas.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zvysfkpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jstaukcq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fpllgnyi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjfzaay.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnvfhwc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdbowup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2alfxsbon.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvbmztd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwjctfu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmlyypp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdpuvut.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtcvorc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcqhmrz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgeszwc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vffyqnqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabzazcy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoedizc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzaagur.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgwpbjb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkjkcpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyymewb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrywhoty.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbwfcu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbbxjfh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrfoeco.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qznrevtm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugjwqqx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvgmbp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxauhsvw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gflzslgl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfqegpz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xofoblab.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzmmyqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqmcuwl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxlfjdf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pczamkkl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2akcdajzv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjudulq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fixtlhom.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhbqemi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzbfuzu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmshehrn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nenyfmjq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gjssxcot.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmtzgsc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjirltd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejzwuk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgukqbel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwdlhd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlconarn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sarfmzgj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgubyow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvpevcc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhimyldp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfoysob.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sltopcie.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbbccay.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvseskd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffscbpi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyxvlum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cakzceuc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbnpcpd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbzuffz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuruojo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbmdwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrtdlkg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnwrirv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvezijtj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quodpwte.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elkseisx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnznyylb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qswqnbrj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usasrmij.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbboqxp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fddgjxqn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2irkqrqan.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkkzhon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osabogcz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbuseke.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjmomh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwwlcdy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaerkyc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txvaftqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvmeryf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yefsjsjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbefyfjw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qugqgtqe.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdvcerv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkjniiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbkgdkz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2divvvquc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yybxcnqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpipmgld.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bosvrynp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdrubgz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqzkwxn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzzhetg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gojmircn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2behaayxj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwypdkqj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2negewvza.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soiqfyik.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eudqwrsr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yspuzxij.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2byivpxil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iutuaojd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkclwes.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flhvydke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyijuna.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzswmjjz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oheaiozd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qqskxlrf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpnfyxl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2prwdebst.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvwyeoe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcvjptd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukgajvd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pawiwopk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgmvvbd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrlyace.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzgcvp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuosrey.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2migbyimw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskinads.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgldeudv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qerocslp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwxfmqs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyrjckh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fntpsmjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vymxbysq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fojdbace.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqxcrz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvpnhgk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchzlofm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zecwohtl.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzibycij.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmklisr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpsziyx.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aatjlopb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2anogytmo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrzmqxc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyithvlp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbssuvoz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eflfqgap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btzokumq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehezuqun.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shrquxuq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmjnbia.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgtpihd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztpwsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxzpydh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuanqnv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhwvbjl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2eedfouyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledadton.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fffxsmnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loqfwwfc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxrbpio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moyuxrwa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kepqkwvf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2crnubswy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jungdwrx.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aueahipj.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxztfpri.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwtwyqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpioaugx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhzaqai.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2suytvuhs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbiqhyp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvuhlhb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhaivjc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjgwpz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppukkgjg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fppohgmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyesmus.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkfetmv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkfjrzq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aflgwtds.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpsayhd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhjfmwi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqyfgbk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyseayyr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zziugtbd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhadoyt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvrjnky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmxesxz.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clexzweh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htogdegy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvxqhax.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooswxcdd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcqqzmo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2olnffjmo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wogbycgb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxruclpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpfevuq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgklrb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uweaeorb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjkwath.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuqwzut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkdlcds.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkssyejk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfywdn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfikfwjo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhaztwo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrozibfs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwnvhzi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfghmbl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xttgnqha.html


<!-- 参考信息 -->