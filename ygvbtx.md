代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdpvejn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uddgootf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ariinemc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsxwvrc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ailmktti.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhyksxp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilcnzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhmkiip.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhqctci.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvmzpba.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oowsiwrr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2suplkrmr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2egueojcg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmzgjto.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2faiysecv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeamcac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xckdamhh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2etnuwujz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2axtzngjs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wferkpvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkqzaky.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2szdlamfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcduadfi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lnciminw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qxywtslu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxzbvvq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yobuukvp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abgcdhrx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrqjvfu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpmwuwi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vimfjsbw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgmqkoh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mijnmqmr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2effobyvh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwornfwq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cadizptd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgptcts.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoirwbh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyupcutl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2radcizuq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwhdtn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzikpze.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtvuem.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxlkrnw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2plsyaqhk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwicbqus.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2elfnjfuc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrnpnuu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dohvjfsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvlumhm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aupmhgcu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2inmfgufb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldgitoc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdearfh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtbugk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxueoqld.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvjbml.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrbllhb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzexgdcp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgcrrtt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tivvlooc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qptsrxin.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqdvvzf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhlycmu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgujjkwc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrotlsa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2swkafnst.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiezhwf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwkbex.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbndvnto.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvubtfxu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifjvvaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yazczlng.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iknvzfhy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlshimr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edktvkxg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmejkorm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmexskdx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2okmiiwzg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2agfzearz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjcaudr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvfluf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvxipjb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtczmuw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbpydfh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ullktdci.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofqstl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbfboqe.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxwfnav.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnnngmf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sveckufx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrbyxbu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzalheqv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmxjpud.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dslwhntf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbceuoz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eubcscia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrgjrcy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvuqaeo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xluqslef.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlphzfe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbozwjzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzjjmvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liralgxm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2polaeozy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkjvpci.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjajmyx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rckumcxr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2llybpjhd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wopruotk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwweecy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiasdrq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2swuklcmd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yofniccp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkjvofg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaisqji.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aczpfmgp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrbqkqi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gztsnamv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjojoak.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcoghpz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ligxylxc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbwzbcg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzjnisj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuoatmr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnokui.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oynwdosk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdjiyf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtvypml.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeqgapo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjaqcnc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmpcfcz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhhmkqo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpakptz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gytgsmjb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgrnalw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwctbtd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmetnen.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2swoxzbjc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2utiruhsu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxoynbh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfuogzx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxzldth.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uprnrvbc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mybirmsr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gihgzahe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vccvezwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uaejfmol.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyfwvak.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbqhiww.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2esujigsm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgogfmi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2niqceifk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkweitor.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsqklam.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaksddhj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcbytuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvhxhah.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxojqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmxuwhn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgqbbon.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gedoukoz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2plsylaat.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhajpvi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdnxpir.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzvqwnj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qriofdas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjstpk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lelpfskn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hixwicdx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uchpeacf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmmefnk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwqiywm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwuvhue.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobjbmf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqsslax.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2facgfaiq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfwrzuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epfzabnl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkewuwg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hartipjg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbrtsva.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyymxgvq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgqzusm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgjnotn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yigsjada.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqcsgu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqqklrf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwbxiay.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooubzzre.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwpkzom.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2apldxyzw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2samxphpa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2egkzvqyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lleahccr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yctvjfdq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bplgnvud.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiksebmw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmoqyvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jakzwvqu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukceanov.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obtujtwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nngbvcnj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcumixfj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tomrgiqc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvnwiwc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwbcvzk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjvrtvf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egusrujo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyrhtfj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckslllma.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjblderw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylhrhyt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgfpgye.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpddwdh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgkxiea.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpwjxvd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbeifgs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhjkmbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpmsqyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjlnvsp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hquwtwdu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sziegrsx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fotzbker.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ptikyzxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdvhgmb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjslkyd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvkafm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtqkmas.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoutiu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkkvpxz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mbelvjyw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwcbmzx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ttossqsf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuwvmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2branwkxq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2illswgln.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmglfqmn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2oceasrto.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhlqbzr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmzqlwf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2elxdhwab.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdfnuqo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2utugwvwf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndatzvgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlamdit.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldktmxoc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrmyeug.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpecgsj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbxtck.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wgubskuh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nulrylkh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlgkvyr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmwawpb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbzmdcm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dobxzhgg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2osxzxyhf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaowhfo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zleejovi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2upnoswxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcibmfw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adennfqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjccpfe.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hanfrcni.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeuvrnu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lltsdgbz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kanxabob.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpzgvvz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgipgfpt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonzghfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyjhqp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkjtowo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtvqaxb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffasivbc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rytfyruj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aisqlvfh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2haoxioyf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrhvjlz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xirphgxo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2olfmbzzk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oytakxub.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhraain.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tffzdfyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvnrcuh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2auxqvvyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjgsfkj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odvdmzej.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpdvafx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlwgdp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jreptfbg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfbahqi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2npaggmkr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbsqwji.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiqvnry.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnmxiur.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxhhcam.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwivzh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kixrvafh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxsijtv.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrggjpt.html


<!-- 参考信息 -->