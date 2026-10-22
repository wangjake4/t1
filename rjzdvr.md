代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2duzhxbwf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fhurohxh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fafyxaqu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjsyaey.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2krkdtynj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlkklue.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yubmjxvw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2shopgfrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kblokmbu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwntopc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsadlkt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2znciphoa.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvbvlox.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyfcyxa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncycgtca.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beurkidj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlzfzbb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgivasdz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjjjoeg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vodhprhq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdpyihw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rddlvofl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmwcdg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvclytvx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thnzjnlw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkoklaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zduarejc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2siyopufb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtsjezs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvxrmj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivftkuvk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjawvirp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuzvqon.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jupdvkpp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampsxode.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2epgvjoik.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtivnddp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlnpknd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezabtikb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2phwyzjkk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoivmkz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmecfwe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvgsuud.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimijtxv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nugloxzb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijaaer.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2scshnfbd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvdnajm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbtchpe.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odkbvjao.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sagryhee.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utcyrnrh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktspcebv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxkoqke.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwnhfcw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rckyxtxv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpexljbz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2isnqqgag.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqtnyew.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqmzsfw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnsmdaa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yipzatgx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqvoieo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2udazlhvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmizoro.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vflvaobr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqtnrjj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayacyspf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgydhz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycychatr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdckukw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zynzbtvb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2etjaqknq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpfbjms.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqvyvz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmttnc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aanailzo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikobezmy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arjyxqmk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hksspohl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvxwwll.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2afqoozla.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wggmhljv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcpxpkb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhfwmps.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzrdela.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtxbubq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrzmmqr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fykmehtp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wafnltin.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkydnknt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwlopj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbwmvt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2opvpxthi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2phssxend.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pncgnwsa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ioluwwmq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwdkjij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2foqojvfo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnmiguo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iejdbheu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2renkfepp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjxlhof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vksapbve.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlmaikw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepbhouw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjewvaev.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrhrhfw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnqddcq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgihikna.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cseltnvx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2whgqykam.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjvqrts.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adwazhyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwdokeg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzmmcvd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzhowb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2trwhfeom.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkvloaj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwcgfez.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdedklgy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuxlzvc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnyckst.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2depqlstm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gkicmlye.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2arxlmiuj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eedwscsr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuknqnu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoqmata.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqexfqfk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ljigdvde.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2psrivhav.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tigxfzmw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzreifbf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iouqlyum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmyqumj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmibkza.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fzukqsqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xggxhdem.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dygyfwsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qajpsuhg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzgctaj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvarpdf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyqywkw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2duuozhpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdwastj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrihyyx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dduiupey.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2admjiywo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbmkqfl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjefkhen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnghgxm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdabmmpk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cputhyxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzqihzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oriufsrz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpmveik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbfevgz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxmenh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrumcfu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxircac.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbimyjql.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvxfsb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjyfpun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qevjrhpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cglessaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euzspzhk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vknclcni.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkugxwyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdyfczk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnudorx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuymqbv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dajsutde.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbwyxxj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwqnpct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtfqcea.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjxfvsh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xomdmgve.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iumsoydu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpvnhan.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtgqfqy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyhfcxq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaaeivg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2enscsmgk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mocvkede.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clvphegl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uxilrqsr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdmheom.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmshtl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykurcyja.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gicmdhyc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkholnb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejjxmo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzweste.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2auuybwir.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mzovrojc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2argosexi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzynbyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diimpfxi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qudszghw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpuksdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tyatnerz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxnhahy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2adqoipcr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cahtkiwh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeswrsj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wokivpee.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jzozilec.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawiwwua.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoltqeif.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnmiqoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjwksmh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmzsfgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2adfknhbw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kledmnjj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grshoytt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgfzfwv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcahqmoc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2izueaben.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcvttxd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcttlgo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2niacicce.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2toygzlqw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hivjieni.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dappsczk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmpnncn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2puomuums.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2shntemzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrnzxdb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2agwhlaps.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fttmidhf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2rncnnrqk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrqtfdd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwxkgnz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2prizsnro.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjscfuun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzlzlar.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjbtkhj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjryokq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2elqdcveg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpfzso.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtpsxgt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrezcch.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyldxub.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jamjzikw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvimrlm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmhbalj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhokxyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bypbgrcx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdpaypm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fydmpzdo.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prrurpsg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onumthpc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgvkyjq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlyjsb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuuandy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbewcsvm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpkpxya.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmgdeob.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2akgtywdp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmmnbcx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcckwodd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfzzmxo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmadixe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkquuoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zukmskkt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2darzsgtb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoqhkcm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2duzqpdsk.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rytqobge.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftehvpam.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tigkwtev.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ielgihbt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfjifhs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eccealpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhbtpza.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hremmkuj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yekhungv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtzogwk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nerzaxcr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprlbgmp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyvjfvo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkvqhbw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrawqsbd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqzsual.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2feqdlhyx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2blccyubw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxiwnri.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyawfcr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzklmyp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjyjtak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xadvndmi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2icsyulbi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icminezk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzplzuhn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayavznpt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoptqqv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2tukgyefx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2msgdnajh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kncvhpsq.html


<!-- 参考信息 -->