代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqusbbs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vejcqdst.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2afgehavx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2khmbgwbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoegisvx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2adtmaixi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxuwchu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2khykihjn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2csbgfpxw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iedfkdot.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgkdatq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uktasfcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvvgnha.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rcscxrzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggifutas.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkhnpga.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfmhjfp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhgplxr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zahcktqf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvygbns.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjtmmdj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdgfukb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrbctyp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hetzjakm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcumqwhb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkydeor.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxpwzel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlvwjnk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yahwafem.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxncywk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2evopjrhx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2doufpnoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzonbly.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdfpglv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2onvsrtok.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzxvgwm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzjfwmx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wiookest.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqgmjmj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjkjjhy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2spgxxftd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcehtnpq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2amtiamfq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeqfsyy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wngfpdpj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oovypgkz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzqlojd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cikuggqk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqdnlft.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvkeuqg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2duutclhy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2juniolnr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2okjpqpbj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhcgglv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxbqieu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaximie.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjmjfmn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2axfxmoul.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxjwwxb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkisnavy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bczkmhem.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2noycmctx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gglfpqkc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvuedxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmlzloi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iofopcik.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2spxtipox.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoosubu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2juartywg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhtefbe.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsgumtn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtjkcn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuznxyf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdmeffa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjvnzlk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgbdxxh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqihjzu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2karagviv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwbiivn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dfztdvxs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgizbso.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsjoeqs.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwpbfwf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crienmzg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlujvqpe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnoexfy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fshjdgdo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pwypjfdy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rmptfvyq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjwcaun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nykdysbi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpemjsv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpxhwym.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxdrdpy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sosuiqls.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2leqyqrse.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vuykiqhj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2omonftxr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2timjfqpw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyhyppi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2crfxhpqx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbalhh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpvjvyl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fvseborh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtrdzmb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cvktijtu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwiuoqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcicnbzs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gubojmzn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkirykel.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxitnxo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpbbklr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtrdvur.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csqeonya.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsccmka.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gunkeonv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxioztf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaigcsm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koinjjvc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidwioos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwdgpok.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbistjgf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2djanasvb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wddvifcw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnmhpjh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2felftdfc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjjgxtc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2twutnlqe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sltyhfjl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xuatzmbe.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcoolr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbktckx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tarmlqba.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xewduspc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2odehrwhz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjhinsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnvata.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puvxxwta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnbpxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgodnpg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqcckvo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzauioi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwuxgm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmfesah.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oczgtqov.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blbzhivh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkwjetk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibgyeao.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzqfism.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcxqhra.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcumbxu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlfupk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgysnhuu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvqzeoc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpbtwta.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2aekjompo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrohexr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wlicatus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrvkara.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuthfxps.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjemvph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izlwjmnp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzoanza.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlxqduf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcfkjwo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtguseos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fktwqrdu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaetdqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ngivpywh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwngsat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2banrgfft.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyaxyps.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfdjgud.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rznnytyh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyaxgyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpubgyj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvtjrxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoutnlm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kktihpvu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhzegfb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2euiveytv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kajbtgki.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtacbctl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkimbjl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhirfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2npymettw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprrnbqj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpmbuqx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvalgzbc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdqvpln.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqxevqj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsfmmdm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvrhzfs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chtalqrq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irormmzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bndperzs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2udgotpwc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxubstvw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enfxhbwr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2oqesihjz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgprpzxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewajqyay.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rndgkufv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxqwxgy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2drnghmhc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsfrmbc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hglsckky.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2myojywef.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmmhatk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2txniwgeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxzgozl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oboqspel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wphgqoja.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwcqsoj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwytipz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2linehvrb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jzadiwct.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rughkeox.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2umvimpnx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2homjaoul.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsffhysx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgypzra.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvwkkzz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlwtmgr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdfkczm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2znrkcluv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpgzxgv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zohgzgdo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxqtomc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbswdys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlibfmvh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zplwdgqj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiavdcs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rclsrrnu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bleeenlt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ejunbrio.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrzyerd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkacorwn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiatsloy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmydvagh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wiijbyoa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2uackmwpn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtwegyv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2utrqwwzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjidzled.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2syfbjqek.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpglvwd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjgjvo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehissf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiitzyt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2lttctfoc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwooggmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsocmpku.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqvquwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbupbnx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbyefdz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvexzrb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwgffoz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phapsrie.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imirnlnn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2psdyuanm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprtpgyj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewbimwy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzplhbd.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2laewraal.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkotmdk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlgwwwm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwjizso.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndqjpgh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjaoses.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhxndcc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxwkrkm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhggglb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoviqsr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgxmitw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoehelh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2teovcvyb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qinaoqqz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiibksmr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwkxhit.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpgqrrd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2binyozwv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jowfodah.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2auohejtu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2emdsksnz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzezklu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuyzubx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbefqz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvvjlbo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdmaphr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqysylrn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjnztzz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbalpush.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxdxyfz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikrmce.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rghkxdsj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnlztvc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyaddqi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoivegm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpamtybd.html


<!-- 参考信息 -->