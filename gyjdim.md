代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzahwvv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qmabepuz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvbnlku.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2osnqizud.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcqxdit.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfoywgj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihasdcsv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvvrlbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgnmlau.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpvhgaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2viwisxnk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmukzkjn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bughuufv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjjverc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rshiomkj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkadyhz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghggdfjc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnbsmxd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkdhrvo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icwomzbj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnstmgl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbmyfil.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzswwoue.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqunasst.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmjbhnd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgkfwlv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxaacoi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcobbnn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lulkctrz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuobqcx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2welnigui.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wamrxxvt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yolujsvp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2itklvrtc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcanthuc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rdekcrzt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwydqtwl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iipaccqi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgqdyjl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oilguppb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqcxbgx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfrbpqe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cugwkeqk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrvsaat.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhdhekn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fklnkzyq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dphqftmg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqkxpmy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ohinnewj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdknily.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chtsowhs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qheuduqp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paigecnt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqxcrim.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2laogycdt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sghdrubo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpwsite.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2eywxiucx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuzpgif.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoyenph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkqicwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xplcuxrb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbsbmsz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yleiycet.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkpqczm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atcucpiz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpmtwoe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmagdrc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aswumlbu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efjwcslf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2auzrzwdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zenelvbk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2benhkzbx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2brrvbzve.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kixajviq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jskbrzxh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdihlcin.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raygnshi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmrjncf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdooilrg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtgokvl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwyfkwk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpbzidf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjkjgfx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxuegup.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnruemf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvitch.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfwdnvo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhsbqbf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuygoqpl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xympmuuv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jowxhohd.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgaifsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtvnvei.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fwywigbb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzgbflu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfsvkoe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgylzmu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tglquter.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2voziceav.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sacxgwwv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2efzhjffv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrfcljo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbackscn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zucbelfn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqrkkh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrjelhr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbgjdwi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwlamck.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwkfsrn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esdaefuc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tqghyrww.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjtnjcj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsmpolw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kstiekmq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrenskar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuytbtei.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cccjqhwl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwdbpm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2msdguilb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2siyreoet.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxgnldj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mudklwkn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xcskomug.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtdjiol.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuoffga.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhokgkzh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyodeoe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aehgmtfw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlchuxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeubiyx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuadtfhy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyykjuh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjurzugl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbymhdo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2smcwrfss.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iblwwrqm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwxticr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gobkndwa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxjktux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbddelt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aestkbkb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvamgctm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhnyuqu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxdamrn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnpxdqb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2euasiwfs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvmecdx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2flbmipcw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltxknvj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmgbyuq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2scpsrgdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vrikkamb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2iskivsrt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxnnmub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpimorw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nrauprrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpteuzn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzrqpcx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzyctc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imsjakgx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xizzztjs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqbpbpo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmfgtc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edyohjzw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeccgem.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtboizto.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldsmpt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2luyvaddk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stgbuexm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hayskbzk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jandejdw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfwmmd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kggmffns.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uruqahhx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfphuqwr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhcpavc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbwduee.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eebaafwk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpjmows.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqemnusr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewussljd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfcjjpb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqxwyme.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2arumrapt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkdcefr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzrsglv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkhvpnr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hogplhez.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwkicdv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhboubtr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzlweuf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkuduof.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqhnygj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykslpiad.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqshdba.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjyhaaa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzhjxsm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjslzdo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpobpnhu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrknqcl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsblcyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achvaeqk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vldjflgf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xodckuiv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwknrbe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfojgco.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoetavg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaykbxhp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxluzix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrofpdsf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhvkib.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2djljxlzz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvrtos.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwfokda.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmolsyia.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igkomvnf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmepqkg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pjypflvj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2woxlqemz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dezolxdm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhntyka.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcdoefp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwrbysw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2myukjvmj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbadrng.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqbfxyz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsugwrs.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jltefapv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2szwdxvga.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ewowlcit.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2eobngknb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2heckfhnn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjvploy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebeopvd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdfibym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhgvefe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmklsjt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbfyspl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iknteaqc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2svqfrxgu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoxhhyl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ylriuvbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsjcwij.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdclgbm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2veubuode.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ienhvoex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsufgeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oevcwidh.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuxydmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrqmuok.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vcopnmci.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsikolfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrypglzd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxypggkp.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouerlmrd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrkknsy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkuuwwe.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkcaogp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejphfouw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpuwjxn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrytbby.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2djpajzth.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmsiaji.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2moqasfdl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcczabth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2creuphaz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvssokw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgrpmvj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qahwotku.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2neoxhqle.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bofrhfzj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbupomu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2idwcqzpq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmordrui.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtudrs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfnfagh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2mheerlrv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azcdewzv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqnbxxm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhywwoq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxffyvmw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gysirmrm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrepkmpa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2onnndnav.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzkuypz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2asiiseht.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jhprcisv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhfrojf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vidprmyg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzbehvq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2godrlvmj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbneogsz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncosknxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtleppyi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxyfkxb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpbosma.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rowipsea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jggeswqj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wykhkcsb.html


<!-- 参考信息 -->