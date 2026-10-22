代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxdgln.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjonmpsy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvrcgen.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2khzqhyej.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoctqkk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pulpkhvh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqsegdd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2birebsgb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2axjriuyx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaeimfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsecbob.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2djcxeknq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvxfocr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dapjvoew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuustis.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtinofo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yulmqzck.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqltpgt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsvizia.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnirjgeu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2magwukfp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2urkzynmk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djzejcmd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiphpquk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eceranhz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpdztzv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrfkohh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyrrfxw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2negwgdop.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbiycxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmmbkhj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llikccrp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whkjgkcx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkqwrdu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxygztr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwywntxo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zericgcr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnvpgrd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgarcl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjwdsbx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpadflzs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2edqhozhs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2itbwpaey.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxyaawx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaetyhu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vexjavru.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayozlrky.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyyytxr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2puoyzzxc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2quhovkjk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeczpcp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lndwencx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxorhzk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolnlfh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaubosyo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yirqftui.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ledflwtd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnectct.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrnnaeh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2webfvkmp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwnitqj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeezegiu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prydkorf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovobfelh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcveqcpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmftrntm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vlblrwox.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjynedd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmitjxl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaejsqh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzibyfj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xahlfrdk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvqikh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrogqpu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyipcsod.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkddqxa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ginxrpcz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2psucqfcp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wrirfejv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjtaeup.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwubrnk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnllayfd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jokkmgzi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwdenyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyussll.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aljqzhcu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkolowll.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oktjtopi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2acibwhaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inhcylbp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxriubt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwjopfv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcxqztv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslqdejd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khroolzx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cntmmefa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaepuld.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2owkbkodo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fytyevdv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmlagp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeniwdl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxhwucb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcjzhah.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2widmbtdr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zggwawsq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhjwthi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtxsoql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqaujuf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptsrlfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtsdrhe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exxcxyyg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yspgruud.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tkngljcq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjcgbuu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tamalfkn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dywunnry.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icutkmul.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcnretz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcsrnnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmshbgkk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hibxfpqu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjwrctu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieizjwdn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xobjafzr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2leavljvp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqxxpxe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqokbl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nvglwhed.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxyqevi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjnarql.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2anehgyci.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2flrfribn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzbmxjk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbdyfcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2phrpuowe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyecnwuz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwgthrd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihltozmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqoirkz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbkcdrr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2luqijowc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pkavgokh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2olahxgst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpkkkqt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vedqzudt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irtqxzsc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2azihfyvd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2odtwhgay.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bosptbwx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxlhihc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmikgsn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sobandil.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xomssjam.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2covrhfds.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2whrkecmq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2buyylyrz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vudtglvw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uynnfacw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cywmoydy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2posmosod.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjqcgwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsheqwxg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2eesxlduh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiavbqpy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnjhmd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjazesnj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegqbuxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bluyuaia.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqquvem.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftetiddp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akvdcioa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lmevmidm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2eycsjbou.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwjxdmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrpqtll.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhatpgm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpogafne.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzxhszm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grhkzlmd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzmwuyo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iofaniuf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kubouzev.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylszgobx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2afbcvjyo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bblyjumb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2menmufdy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uadhimpu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzgxre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jclxyirq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcvbrmp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2swsyssip.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcldfzzv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viievznh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgawufvc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chonkyey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2useutzgd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jugauqhy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oghxwjpy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsdmqvz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcgmqkf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfvuiwd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skckswcr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgcoovh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvqsfhv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2etqususi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbncdjw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzraxutq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2egmxvcwh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjbbdke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytdkdez.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vmifncvf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqwrkzx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wifgznci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrnjjdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofrtbjq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxxbxay.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qsorisyv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2urlctaye.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbsuakt.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunscvvd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiyccaa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmstapeh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwqnhj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoiigaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2udrxmenx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuvjrtv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaegnvjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2kaltippu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoxvfiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkleats.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqwhmzo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsalsncm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rhatxcrd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbrpoqf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxrijqy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvxtlze.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejumuxr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipfkzy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2thranclh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkmpwgt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvqxbp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kduvbgng.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbacapd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bnipxyjm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2niihwhic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhygrpc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgjjemn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xwduzqqk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2glnflspt.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnruutgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjruqnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2injrvkwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdobzfpp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxlbqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbsdhcz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qyijlauo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztyornr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cycforac.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jignhpja.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tolygqys.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2flgahmsh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2coowiaqw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2snqizpuj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsksblvx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xebzudfa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpwaenx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdqemap.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fyparxdn.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdupviu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2weogmgdk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcpoqno.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihypprn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzuoqzl.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kwomgvxf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poipfkkr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gedvwbwo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkotpwm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eullmgbl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cznlxjwn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwotbgj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhlgwqa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ozimraap.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgjuhpx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeftgin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiuqtue.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qomohxuk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2buqptycc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrahiuqf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2acgjqugu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2geuurwvr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mstkmfpr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cauujjjg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2doydpukw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spzipchp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjkhsms.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaczhqv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlbqchf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmrmxn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjjqlpb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wteugmwh.html


<!-- 参考信息 -->