代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgockjp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlopikij.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sagyhzkn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zddsjnyb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfpsheb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ttktghhh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnyonsf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vllrlcnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlfjfob.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cfopuzdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgmniut.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbqlcau.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiedysl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqpkgvo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwgruwu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnnwgj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrlexzs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzlvdfc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfzwijs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wudartjx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmygbiox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdvuimg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isvtrmso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgpxmlj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkqkykz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myabbjwb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jksozwmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnlorat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrxtplv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wztnmfuu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2niofxnkp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zimylith.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgggljpp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsivxvqt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cagxhngo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqchyay.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2stkbxvww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2buzespug.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bialicxs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wufzvbuy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwesehtr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdusiuw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrdklmo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfeyjba.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqzpsdh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhmqhzq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjsbbqp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtyhrjw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvihfpa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlefyqyn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhjzaas.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjejesbx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqezafw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcljrmx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wshzunue.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvwlkwp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuyulmp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbtzjyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ragzeogv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmciwqt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asuuxtsl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyxadtr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmffgdg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uemctxrb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2imiyplic.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glamxyuk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiyycqf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyqqbgw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwghsjzb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wftujuui.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikpqow.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdicixf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jyifudkt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2diidfbpq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kjixohxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhsopbk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvwgyrn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjoslwy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esmggqml.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjqlalh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2icwktwuc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ootarygh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqarldwi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdrbqze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wytrwtsg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnetlev.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeipjyi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srmmtukp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrvnyhu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdywfd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yufbjryr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuabbrg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzmnnce.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2etndionb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzbqfgr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dnteqvzt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkrhhwl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2asfrkdlv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaidkll.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzdiglw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqldbzz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzwrfdv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxakfwo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadgrqil.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyowllx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhgolsq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcciuvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmigjff.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyfrff.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuhasgz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmumhhvv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rkofwmyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiommvl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdeznpr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oheccrij.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbabsfn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2trlpscko.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnzaart.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrlmmer.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgaphjc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnadddg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhakyso.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaedtyh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvdjky.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzopdmp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lsshfwis.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabzkxhm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vpctnrhp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tpufduqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsvayym.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rogndpyl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2owlvkcey.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pehietrw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjrdjog.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2arnerpeg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhkwhln.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymludnjm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzlgkhn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zccotuzv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxuttd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oicjwqrf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obogxbbp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gncgzrxu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbtfqdl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2erowtgae.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzlnoje.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uawsqakn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkydrld.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxbkgel.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltiowif.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsuqlvj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigrjgd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgsizcy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbtqzpm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxrwvfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwveghw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2atiwdcbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfcgwpd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fehcvuar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gafzqimb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rduelmre.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qanqldio.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzssrfel.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irlpkslu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2heobnncy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrwsjrw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcgkmbp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aojisccl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2eafnehfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gddgbtsw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpajavrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrdpnrm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qymmbklq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbacieyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhvtmnv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsjghoo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvdfoaf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2znpwvjlw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoliekk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdknohyl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpecygqv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilmlpd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbgrfdl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtmxfnu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdhpmgv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obkztscu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeyhnvm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luvofkfe.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbgxpv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjfjoj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcybycw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnauunz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibomvbbl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyhsuqh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngraiszu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzovqef.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwyiuu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxgjiem.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwnhjb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knnmlaky.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sliawmqd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2amgrsvlr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwkybtq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrgbjzc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyblgsc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkuymtc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkjkwyn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxuyvvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzrtmpq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlllscnh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolvkena.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmpkmvq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxtinxy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceakbuyk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnrsepr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esiqdver.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoowlbt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qahoajbx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qllenkbr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqceizq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzvlghn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ojagybbn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuqgdsc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2metwmapb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvhwhks.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkpxlpc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdrhzrd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdotjq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkxpgre.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hqauukrm.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oiybacas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjyacfc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2otiwzygw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhfiegm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnodtebz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azckwguu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tpofoacp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuhypuh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqgqefq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmusgcx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvjbfdy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkkwydz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mfytdnip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgkkwcd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2urmyudnt.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmraeehz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2iontyhod.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2keiqblym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2subqeguo.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoqevpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swtveyaj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2epfyzgzu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtmfomx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdyrdgs.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oreplfpw.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bilrrcmk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xokzsweg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbwlnrq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eebopaon.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lygawbxn.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aeknyyui.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerknral.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwffpcfx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2riiklcko.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjruvgg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrgghht.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqlynbs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2liagnhhp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2llatyvdb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbkujqj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfvjexh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqyzsjw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbocrkjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqieqcpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kciynemt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmveht.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzqdihl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gefdlpqj.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqvoqae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrpdcdh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdionumq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmhozjy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2facookdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2blwikjvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2omnsuzee.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpdaodf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiumfdqi.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uhujwiom.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xubnmdcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwgdvqo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbdoyob.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsqfjcz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufipshgx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zniywjud.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgniyyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqsrlos.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbehocob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlftaki.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabuhes.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nkprdxqf.html


<!-- 参考信息 -->