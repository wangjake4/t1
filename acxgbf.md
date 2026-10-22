代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsddgjjh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liymztnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aolhxxpl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxlbavw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrurekz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmaufoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvadixh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2whmloyjj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sexlxsav.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqwjdvd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxhxxlm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gatdplcr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2izotwuyi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lalwbjsc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzsrpzt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbcylk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnvmpvn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hwigxhwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqydkjon.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvmqzus.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlbflhq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwbfikm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbprkaxh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vopmzsgh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzaisyb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2iddjykeo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2perztzmd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azidpruv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnbyzbq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2begeolgj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvptuegt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjmchyo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jugnwvjk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnolnvx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujbjonm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jtywizwy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pveiiigw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqttkha.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcovdqe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnadeck.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiznltf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdcqfpn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzmndin.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2riptnftw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiuluqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxcuwg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2psdezmsv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2chjrsrzc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spaqfgrc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwnehwr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aogikxlw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxreehk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sleefdkr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gucqqgxh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhhbhbd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxzjmxi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdtybou.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjzkhbc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvexuyv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszhbub.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhvievl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyflcy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvthtoh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzwfjft.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xyepnwfz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsoejry.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnneiiie.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xggvlsmp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlutidu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqmpofe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiuozqb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iftkbcdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2buaukoea.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iekrgqyt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhzhctu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlhdbxv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hguftqae.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imlemckm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbbbpca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuxbwvc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jaysmfxk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiilebt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2scosdabu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwydfth.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfemgtb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mntglemx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiouqrh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqtlxv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjflxlbv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyotydmw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qymstswu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgecvum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ffupdxtq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjzmasw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcfctwe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stdedmjh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvsqiba.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiwwlam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bttbzpph.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkccpvb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wiczuddy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwkyftt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kivtwgnq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tndhbeou.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mutdsomu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2stghgdnt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lskztdnd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzkwfvn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2elbvncop.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsuebls.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnscjyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruorulea.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfskexbg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmddwygw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrjmnbm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnellui.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcewkfr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwystxov.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szfjoxjy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuaujwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsbcldf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcbfpbx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqthobiv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmvpygu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqerbog.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibzhmo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zodazsiu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beaisfsy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qamdrcfe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdilaacp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ronxcqzf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ysixlcka.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exqwhkmc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdsbvts.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxkrssl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvjqaax.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzokdmt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2daibvnhj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvckxxk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rklroodq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyqjhur.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sywlincg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jknohfbu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2osgvleyl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2godjboss.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjkodlq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqvditf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxpxrad.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jkauxgyy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnirkzok.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggjowyl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxiocne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qbitdtfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2frpbtwvu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqryfur.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2orlxfbnx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlenveo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2earealsy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pweozasi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sodqcrgm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujocwx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qitlkjcd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqjlfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbiinkn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dlacmimf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsdekha.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlyszib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2forxwskm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpabfczk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljciqkq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duldsmin.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfqddqm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgbzpxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2prqlnxjw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2limbokre.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkmrpap.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkismlz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbfqslo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evwxqohi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuwdips.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkycanzj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2iegfozwx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aizxdmuh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evolsagi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aencrnyf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2evmgnkvu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxajvhi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjndnxr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwxyyk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjzepxr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xluqwudz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtvhzpu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2orjmjiql.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgeouzq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcfoikc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oemcdsqx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdlijqg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owsocqin.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcoyztl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaeezau.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmyuxxm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sivxduri.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwytxfk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzrqzyj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtpnom.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szykpced.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chbtijut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyarozxc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwxlejt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwsbksz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrohlgf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwyudlt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zdntvesm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqcpbfo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gyccpqzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2geanrjiy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxlnffu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjrxlxc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuugtnc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkbhgh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrbxcws.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiijohgu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebymcfvw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjshvmf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jklzpasw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbvhhzy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pqinxzua.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dulpravr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otrsdnrq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkervxu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpcmkgh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrcjjkj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fsavjlel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vokghizj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsdmtde.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqazidgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yaihvnrd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ummzdwkw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yddskqlk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfoekpy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2odbxjqik.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2bodrgimo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2saagwodb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgptpvcm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2muuocfdq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxucoyc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdjnwn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxkebip.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kllsdpck.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2guwmnnmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqhepzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hdscgjxh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2gdspcizo.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2uekrnkia.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zefbjwff.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwyqys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaasuyi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dewziyni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quppidrn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqtocxp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxhpskl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcyaeew.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpddprd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfsfgrg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzjmhkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzsiuci.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2awwulyut.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxazxac.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvujkr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukjtwas.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2unkfwniw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfefjej.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbamoui.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pweinvke.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsypkhdx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2umzsecmc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qczeepim.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqcibmc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxbqrnr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqxexzp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqmclwl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ruixfwil.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahegdmy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2emtzzhzl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2djhkwsve.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqnygwg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfwdbe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2giysizks.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrotntfj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfstzi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdhmiqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxsxyfl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcybvinj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwudkwf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkpwdz.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqjoxnc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmogmbg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyisnwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggapzxqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricpppfm.html


<!-- 参考信息 -->