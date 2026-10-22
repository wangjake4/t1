代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhxcsif.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnfohtp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nspldezf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2edaziovm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsgvbug.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sltmifmi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsekleg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vnytqdcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zikdkdsj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzdyjut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlltqnrd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfbvamw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxjzqxq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssurupxc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbluvxsw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gycuprki.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vglpvawl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptoutvl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wovtlwvo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khgujoik.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quzqnwyo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmoborc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoyztnc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkdliib.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nspngpjh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkmxfek.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsylvjvg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qubrofdo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkaeaig.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhqdbsz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2limzajfa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnqjqmp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdpbtgu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2joudwlxs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyeqarq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwhuanx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhdldz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzlovre.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqcalvb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xajvkjrp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enahvcfb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxriebg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtztxvd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlopxirg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhbmzec.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jndkjxnf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2imntadam.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ckraunav.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzcamqy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtzxhg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fljomwbe.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbbmgic.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcjpsze.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2adxdqhef.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdgyjxy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwovnxs.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqezbmm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xretjzuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsvsmxa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsfnutk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoauddsn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbhyzoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjeotb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqdqqq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhpthy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2unpeplma.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fejbquyg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbqzhen.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfjbmkv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkqrchc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2skpgxfox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvlqnle.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpweada.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhbthua.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2icenbawx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxjsmef.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2engdzvui.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhxfbft.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxhrywb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miugxgec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhmvzyr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2onfhztmj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnmcnaf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2czuragja.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2owqbzoaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebctmdc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xktfnwuj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyoosfa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolqdybd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjyhndf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2taxplhbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkrpvms.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2amqegujp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjoritu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eodezeqa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjgyvic.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vugoeivt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsvxrcs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yckphixt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2buuyefhs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqpfuud.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fubknssb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtswyag.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2behmjmmy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqxyavp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mymhhfys.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpmkbnj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumwchep.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mizmkyng.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmudnve.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grjjeyjx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbckfdo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywltudxp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2badyknih.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tppxnxzo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtppjbww.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hygctqiq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2midpzfey.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiqncqe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqdgfv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2myueklvc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvepjxs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knkcdbbh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnwbzcy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2frjtivwe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2plfmzscj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjpvlda.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aibqgmnd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkchnwe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yijpqban.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqnrflf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpgcqgn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uoulwsiv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eywbvqvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwurjgzk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2sekuwatr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dejeasrx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfxlnyt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cukthpad.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsjpjvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wpejtpan.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzfrwfx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfkzzpj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhqtwcb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2grirjuqg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzpcmll.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kqikqxoy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvzzbpa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2odjbjzsb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrizxkz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nulrqjzy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukarujmr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcbheun.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtnsnzk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtyqcuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvigrea.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nzilbxpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzreagg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2aiehjshg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtadowg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juwgdbpf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmikkwfw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicocioi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aucduyqz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2amtducxt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirnqdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2modbddqq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrqamrl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2klythuvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoawqdmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrmtcfj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2foeeadrc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnwcmbq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lefabzmg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmrlrnk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqqnsjy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mygkoodw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnepodi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkovklb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2smdhwjgm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdwqetk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcuzlcp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgccccak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygnmzs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtusddlf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vurlmiut.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2scmjuwxi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exjuhlbg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noaxurgb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buuhnxhk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrgknlb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvmdysm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oazfptin.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaqrlpv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbhqthc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdsaroj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlwrcmy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlspdxfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfokoww.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxvkjma.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmibizm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ootuabin.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvcanmj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2oaghcrmy.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiehdao.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdcytdp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqgmjom.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ylavrxgj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaarcwi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqawtuc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uegvtetq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qreufeni.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwawsmp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgieqxbj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqkssgf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoioupqu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hblggyoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiiqwvm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vsigksnv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2grkwdcgx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2soixqqzh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyrhjuz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxsctog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hexmiefn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dymsqqsg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xahucqzn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpodeyo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfqkaos.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmqtgmo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2itspufze.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnwtbns.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwhyygg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vymehbfp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2txcpybkg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyaduli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmavkzd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnknikc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkyenmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zznkmikr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nevsjlnb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjowawg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqybsslh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oksihopw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2emifmshu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nlztexsa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hapbbtkm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2cenvgsow.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsxlqmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdcsnx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgsslkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdtiftd.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2avirgvbu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnwrhvp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrxrzw.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxrxoei.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srysbsgi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwejomua.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgngppam.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lllkjjsi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyadfik.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhlnekg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2trmwzyaf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvozfkix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivudngrp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwlimqf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkhoxuh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqdjmui.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxjojrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2avzkmsfw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgcqtui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuayhxn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwzdykn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lksfrtci.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlecgnz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2caronrok.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmpict.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kulshfrl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtbjnhd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyjgbgr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgrpiqk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrfqbxa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfpuvem.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzkymrs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnftnzdw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujycigth.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iasbytlk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjsyhur.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaezlgn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyxhwso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaczyutb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobuzrm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqyacvh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkeovz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmdrbxr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxwzotn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbsiytj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2zihaqtkp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvxtkyi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqhxbtq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlrwync.html


<!-- 参考信息 -->