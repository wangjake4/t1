代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzbaucx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlmholh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqmwpqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqtsvh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2chdwezli.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdqanuk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eghpgoql.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vkquspri.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uayhlqlw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdmkwdo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eckfybnj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2euzzriqd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jpekplsj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpdxjnt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvqydfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xiekzbbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzddbdqm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeuhcqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dltltxqd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwyvfgo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qrroopxa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbhgidd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrnhpza.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpawmwo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nawnwltw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqivinx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gffxahir.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpfobqj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfitiatt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbdijcb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjejvex.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slywvzrr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoxkvbq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjemxjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzzmsto.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdrrryh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczoirqy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzdvhaq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxegted.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dynndzco.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bybsltyo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtegcxm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmzlooh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhfzsem.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztrijav.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhibnjk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rblzfenr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iayypkyy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doeqyzyp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnqgqmk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvxpcpk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vutasusi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hikscoxa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhpdhjl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmjwegh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmiqlmy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtdqogz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuuijkj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzezgsc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aypajikk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igkjjcwj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2utadyvtm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2plxedweo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhwvvro.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wibwvwvy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2psuwsibq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqjubax.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhebims.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtwpbqi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmallldq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2puluxpjr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2serflrag.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsdljrg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwvlxz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhwqoxs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcvrvxc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qppppwnm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnhycha.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbrueyw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnttdui.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkvscl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbkhmo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omvsylpy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxojyy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggimps.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oauzotiv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wknmhegd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faqswsom.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhsrni.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uecaxwxw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhqfwwc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2brmsqdvq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hztpfikc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfojrvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfqvjdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uibgaphj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsdyime.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juxadwku.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2temybceb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxbnqwe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vynlyyzq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrwjufg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2khoxzthi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaulnaw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfqpily.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoorfsx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zalstnwh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkqkckr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yllpjkrn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdncteo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkibjdm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oflogfou.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcixjgs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otyxxawr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rksakmpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbfyvxu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhgviwd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwxmdr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ioopstiy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmejtypz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaluceqj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyucioan.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsovdond.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pigxolfv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcmmtbj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdfzvzi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sknffjvc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziygswvt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeqsjov.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tctxpeza.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2utnbfjlz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzwztxi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tjprxtaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpnobdl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfcuslj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2uybjqvre.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xuueyotk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2usgsvfzo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzmjory.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqcxlwi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pclxuabw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoaqspa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqbdiui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzigekv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibiasyn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vxulcemf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkvxjcj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcruclt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmhiscz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwyeuai.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bykvjwai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgxnmes.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhvwofj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2foirgvka.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoqbynm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxarlyh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zasghhsg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rysqtpeb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegyycca.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2llzbfiei.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkicmjv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ububnuuo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bjskpngu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isuyrreg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmvbvwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyangwtk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2srtmbraj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2extodkyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huraezma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzarqgfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvjvand.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkiqdqy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vieoplwg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kudkgrid.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlgcrsg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhxklqu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtkkmxq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuvhtrz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myvqktgf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrsghbk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lncsbmhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhtjyqp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fchcmkcj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwgllhx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqotezxy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bizuwbvj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2klvnyerd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgtrfnr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aempgkhb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oaobmtlp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2biiotqgr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhidxzf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qccnklcn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhgimre.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uoogciqs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tphcwupv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuyvbii.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xogkgtng.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcjkagk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbdjwni.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2guilywoy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feznubkn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nugctvsf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2snupnidp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgivgv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxslioy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aegnetjr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2focpefov.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaxebpg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dmehmdme.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iysfbiui.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qxncahwc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvkuzit.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vawjylom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2whuiobjf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2raskcamo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxymujdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqroees.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqrducm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2usbamkdr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaxlmbh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2riirfrhz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtywzvhe.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeeeces.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfsxoph.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2btspjypb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2maedywwq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxpcvr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nelpjrfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvpgxoz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cviwqvzn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2evcnezjg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjefinw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrrkqtx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaxnata.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2skpuuvbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkmnhvo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rfteppeq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kylkdydj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwftnub.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ympuevqy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2olzwhzhj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2coattiil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubnmvi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwmisjh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpkikgj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbczdvhy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hojfbtay.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgpkvrg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhwybln.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2uhprtwxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthhjod.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2wagwxlre.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxljnoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkctlf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfnvjib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuadbjr.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stqkkpwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyveluu.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oturceks.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icorxlrn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuxriiy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqinnmoa.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxwwmts.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbigzjno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyttbdbd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtgthdc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawngne.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qeekocyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiwyokc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoghifp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtyjnkk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshzwqxj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpobyvch.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwujqcp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjnfjfp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mggaeobf.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtaylff.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbvwxxz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2irbmyegf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuedipeo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2csislczd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2naojtcqm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpxnkfi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqzznr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2abhwukmj.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtnbqgw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2byegnfxk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlaljef.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2itjghqvo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlglqgvh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qawvxdvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dveqsmbr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmqteak.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2shpnyhtm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjvtswz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhzpqfk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbfslak.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfmbmht.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvdnhvw.html


<!-- 参考信息 -->