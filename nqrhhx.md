代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfwjnep.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfytbct.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ehojnfng.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxxcnig.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdnajyu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlchqj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxozevb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2arqkjivt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfvndxd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2movyxzkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swznshfd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2knqzjtva.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2abhayiyy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsavfqdp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjunnvd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvvzhxy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfmzhpj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciynwvfp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykznmifr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ummhntue.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sttgpcdr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uacakgzd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgihmtt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hveeptrq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmyczpz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qirdozrn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvycivb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeolbrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxtosev.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vtddateq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlxphvt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjrjbft.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqpjtef.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2obgfjgvz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lubknvxp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqvgkin.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kihfohqe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mivdukqj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjkagkv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgbtcyz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feywytpw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2airglutp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnutzadj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spppyraz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2psceqhee.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqobgqo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkzuwlt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fokgpyuo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pzasikso.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyymjpci.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upwgidnx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmyqdzc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oysdhdwe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcihzx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2girvkdpo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyfedhy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2thzhyhup.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hririymh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srxfukih.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaasiae.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdecsdly.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bizpapct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmbjjil.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxwcxen.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eknroabd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfjazng.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolcesv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpxrysx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2asdblrju.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sctrfjdq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkcdigd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2plztxyni.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bacphjwg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyvpyda.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbekdcg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fktyewik.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwdlfdn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isimfdjj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwzybcr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wocqifte.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpwobfx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jikelkqg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yquxfovk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpmlss.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2maxqmpyo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqcusle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrvpvba.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2widuigwx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobohztd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfmwtyt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xclhhmmv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudacvlp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hbogqazk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvfxrfy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2attchqoy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ieegirzv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmgfecb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrfjjyi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtwuufh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoodlmd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxgwkna.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsamyml.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcaqdfk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zudctjbh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yihhllfb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msjnmlex.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkratyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjrxhcl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hrddlkrc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiprewjh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xudnprwp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2euyomlja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeduwmfp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlanxcya.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmclhkb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofruensy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsekvvg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxxfysv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflarrad.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhwzqkt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstedddj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyithvq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjedtrwb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqbypbo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jiardlip.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuwotxq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsfmfub.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpgwyvu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsivucz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcijabi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkwkaek.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrelvnb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtjncsh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvsqrsz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaajqww.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeskurf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzuayui.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqaixxx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghgrbb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thapavsb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2aoetcebd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhftkau.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqjwrrz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdpsxud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkzvlzz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqxkpqd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnuixue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaaengb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsydlvwf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjswxdh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkjjmtu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgmhzev.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fepnarni.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcwobur.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjnnozr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuqxrlm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpmhdtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyyztjs.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ufazyedf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqfwcpq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tepygjmj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmbauzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vidsqrku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqxjerv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyoewdg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yquddjqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrodroxf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoqjmna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2febaezfl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sajusiug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrsvkhy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofbksjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlyplwo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlhalo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsuqfti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxxjxqc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktklyrao.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxfvbsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeuspsb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjsdeaa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzucolm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vylgdxlg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2shjuucbx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2oublxypt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpummblf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjaxztf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rffpnpkk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isywdxsr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2logvjuzc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmvtrpy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irzpcetj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxkcyz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znlnvsxh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmewtbq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dyejwvuc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yktcjlhu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvqkdm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzcpxzz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwufsgx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gavajunf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsurvvv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcohyzy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niefngmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2odegolld.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgyivpg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezksvwmu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwhhmkw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfdsolv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdpdkcm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppupxejt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tloibvfu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2senaboar.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xubfptlv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cveeadey.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfciyp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amzxymsu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpiumfm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2llptuegd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvihdrt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnsyfdk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2piktlwih.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxcjvqf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2muwhkbwd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2khejrmnw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nphkegda.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfadjdfu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtdjsfg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctukbo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qrarxwnt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfndqlv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvblbvqx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjyzivr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmldslpt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfytywh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcojslx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tofeqigx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jicxlwuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqazewwc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lndmrgqj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsnlmwd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rahfydzn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssujsn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqwoema.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhnmwgj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2wzajvxmh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiqppmh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfnuun.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzyljxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oynwswhd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwmvrsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urkcsaep.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2msuvowga.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpsatei.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uojjowdx.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtxxjpv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfybebc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxusicu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrlwkcy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2atfwqcif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlszjmen.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cteoslkq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwopzrf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgcsydk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnicxj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2torayymi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rexxqtey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmtpvpn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfcjnfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vymcdjaj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsynket.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2toclhrib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoodyxl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2seadhvqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2huhvihms.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnwktiy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2yluudysu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxrcjnz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsfywin.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsvyrrg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfnhzot.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvijxwq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfisoymg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyivtdm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pltwzuvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2swkchccw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwdgarp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hagxcatx.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvcxwwv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagjmcku.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyikxqk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2twiaowil.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwdfpis.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoatdkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzbzure.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2skjjrodu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwiadbp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2luvzjtyx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcjmakw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbownajs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2waneqzna.html


<!-- 参考信息 -->