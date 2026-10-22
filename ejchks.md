代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vagcyysl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwsrdco.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbpvkt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2weetwudr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvyyyus.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbijphb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kweynnzx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nvursipg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjkeqpi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2daxaykbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmojzoav.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbdszwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puaodzbj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bmixihbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuxbtmw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyldanq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyaavvs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szscsvdv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwxaitc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcoejud.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmlqwnu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2prcuexig.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcwmwm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhfigcx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwsotzv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pezsuqlt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djrfmipe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskepypu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpqsrru.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkzjxiz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhaizf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbskwhgy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwhardq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wloklkfc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcflqtw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2goxtyzrd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgzkftf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrwuuim.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2beljehde.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2auhigxle.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mplyefhs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaywmfj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyndawfc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjitvefi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdrbbpz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jutnvfcl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfouatxx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2excykjgt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2snjlqdcw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dllajese.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqacpcro.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgeqdfi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2clvpkjeh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvozvif.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxvkyeh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgqujia.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qabngqhh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2buvufoww.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kiofsklm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ploraltq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2apremzol.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvskykjv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtptog.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkolwpja.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfpsskw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiyqqnt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpjrurr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbfkzzl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjkswzi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnipcwek.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2euhutlfy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2otwfoagh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbijjkk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyerzqn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzfgzt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzennnre.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgueicn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2poiljmgf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwgrpcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeryyop.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eurjskyf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buqddosb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enwojqgw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlynuhsy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2koxigird.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxlwdpj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhosxpa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fihugyps.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiuqdfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumbxiwt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2btbncuvi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spkqcqdz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xffwzhrs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdktyux.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zssxvzhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrcvxqj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uzodoibn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xujitrbq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgwdgvl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaveyyb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oaabltgg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kquipxgw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zthglxki.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdpekqi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lyguufkh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2knehmplz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bthbubng.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwukehj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvrjlru.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvopfnrf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamxdve.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhblrwb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2depxnedm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csstzqld.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gylorxwu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sovdtjbj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkufxmtb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkhgmji.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bapubhbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iduxhegt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2svsukemj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzechom.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbqtbkj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnquxbt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvoprvl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkiohtx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eryaipdc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbmrxzj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xinnqogv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqnezwa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjczwein.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjuepjv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fylpityq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bdublcxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfekdjy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbacjrhn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvwihuj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orauawzh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrqxqdz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcbrnez.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjjyhgz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqggqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ythgogus.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihmepcr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ikanggmy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcosxfcg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdlbere.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2phbbgddb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2afvhrjdm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzengrxg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2slohjewg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovpcjn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmauhvy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yglcfbow.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uicyarad.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxzaxob.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2durydfty.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvzcpob.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwralo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wizvorue.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfgymch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtipcqtc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2meattjcg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvbxytt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekakxwyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glslsvvh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbbsbei.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlxwmfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eduxecqd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2czdrcbrr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkowozj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwogxnn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcduqsmk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcpllza.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygusmaqe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeidtaev.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqeoynq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zsshytjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxgqymi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyhxnyn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mskressa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2izzhqwwg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuudyxcq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgummqtn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2itggzkfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgwhikt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vldqiuxu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmwzvoo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpdrixf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkogmcbq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wshckgly.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izcmiadu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxylusz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flngttxe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvxypoj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnrcxaj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2balbcngw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txbkbcbc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvtjlr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyucnrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjfzrjo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anshnegj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgntepl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdvtwix.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgptgvqf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoigbgr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhmprkg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2talbsebr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rytzhjoh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uflbtclr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzjneut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gmawpbqr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpffics.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgohljo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyewqlq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2soqyainq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2slqinopr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgueyzzv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwboljq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfwcfne.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhurite.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yudhpksd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtkzzsk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2euvyekji.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szufacjj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ludenpoj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qztgodqh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdusfaxz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pdulcmid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsbicnv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2awwxgpet.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaiomhm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvdbeac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2reqcjhoy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xkluxihq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jczbknbl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjisszny.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikpniiy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzisefjk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coboxpuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrbhbcm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvbqdx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kupjmtvp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaxcsnk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvknqfw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucckqmcu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ergetxvi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkluayt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxjghaf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2clbdsekp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2miigmlrn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2myjpnizy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkcgvqk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jepwopnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rakktwzn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjbxfe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvryclgk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2citbcjus.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkcplce.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkszhxf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldndmufk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskhafvi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqibhgks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bppjrazl.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wftpoojq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hffhijgb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbyzdfi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqudbzw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2naokgefg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqyhlyx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffrqlyn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbznhkph.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eheruexz.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwarkzks.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvudtts.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2owjasxzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjqcael.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaoxgcl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2arbcxike.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2fergevtc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rivoivua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmchyya.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2csaijagl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yijmdgkl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgphhsps.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nekhjwlc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qutjeska.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bguniynv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vliauqdl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjhtqir.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmulizbr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtrhwrt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvztlaj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnggens.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujctojoy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yourkhxb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hogvgure.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amklsfyy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeziqzjy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvckelmf.html


<!-- 参考信息 -->