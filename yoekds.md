代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2umyfqejq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxqtqfg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucjcrlw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcsrrlf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpnigb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqznriv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eborgjew.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xyprzmqz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqjyuk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bdydmsnt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2znorqmqm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqphkbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aafahnlu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcghmzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoiaufw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfjmadn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2czocplep.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nplaiqdm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whkruram.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifacnw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieceostv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwwckip.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unzazrsz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwljcdbm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sormburw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhousqjg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xusquqgl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbivdf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgrgyhb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lklbveyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2daoisxyd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rznbnacd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kscpdgmc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjunszp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdxzefl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuoekxf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwexcxcc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjaxvep.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocudhwwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgefane.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2torqiyri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wshupkpc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2idifmjbv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrdtoes.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spsyjzxf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzfvtzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzhjhox.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlehfhsa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgmlqsj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kscixamq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyutvqo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wduxvmuv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyaqgnk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biavyzft.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxucyyst.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqwpimr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnybept.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszeczw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkbmepq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awawxmry.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjtjzik.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbwgoca.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2falrwvch.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbjyeiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhtinq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pollwnbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpxmssf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ialsqnur.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoaimhd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyumztz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfqrlbx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjivahmd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiedqut.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mswegxtt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2onlvcvgf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxftqqi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2elljnrdb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxkreud.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lewjfcys.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fjikkvqs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpajqtdb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myirbdys.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crcludbn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjalpvij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uiinqyej.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smepvodp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dylpbjqq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmtcnog.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuflsdd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuksrvnd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jhstrjgs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbdvrix.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbvaofz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnukyin.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgfjwxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbllfje.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjauddv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wschoitf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2glwhhimo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2evyziuom.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2podoigwa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgzpon.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzqsysb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pysaccji.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rajoyspn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrvkjvt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvyzjx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjpcpmg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnwscku.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgxmmer.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjjfupn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpaqyhy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtolyil.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcffsdb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbockie.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxvzvy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjmywia.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2remsileq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspkjcvf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhtdrqz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyowsqu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gldqcqwb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaowfdic.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nppfczwa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rglpsppf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfavpqd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpzoubh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtyzqfi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qewhpahy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wsprfpaw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbinmjvr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfmzxft.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2unxdgtmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2suiugsci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuymoll.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnyscu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtevfkcd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsosgeaf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjecqdmx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgbdrlb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiaezxq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeihpba.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2spkwuxod.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmkxaui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2daliordq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipysaqwo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysckcsbz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpwvxeq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhgtrbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaauamzh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uonnnprc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxyzphr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghhszux.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvhocvs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zakaufpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2upjxlnpy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pgggldqh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcmuxs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaerehi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tchrovyj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyteboq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oclufktj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nikktneb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2prbgpxwr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imtdzuwn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bscpbqwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skjggbql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unntdita.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgcjglf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqtixfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmouzlkc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmmnuhf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkapldqm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtshfgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snpavsei.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mficsonv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqfqfeb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sphhnzxy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsygnva.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyddjly.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2njhjggyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdildimx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqarrjlr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldigfyxq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bokpdrdk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljorevnh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxemakg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xugebnea.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kclszpim.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwtsjg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kypjixbm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sydxixza.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aysohiwk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsdlmkp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfvwkfi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvagznwz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atfhsjag.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvtameu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tolfwxal.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wubiggnc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpshszeq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgucqcu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taitzfvd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ninavbcc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkqidar.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwgnrnz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dohwgyqz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2gujdscfr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pfunesig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnzksup.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tlilaveq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibwlrv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgiwagg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruovzuuv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeypnkrt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sinqxsir.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eegaitux.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zikoosox.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrbffps.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlphhzh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aficyfve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcnudv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvbetrz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2basxlmqk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2scgbkhkl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjvzavj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nahpjukn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlttfpj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxftkwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrztyivn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zevywctu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdseymu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmqlaby.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2loppppej.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sejiiusm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2twisvdec.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktreku.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiygtfp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaifdrl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxadfup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2igzqfags.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecxjvwg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgfnddl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2myzyokcr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbfdamq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaxrsjt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2grdaifka.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcmzflf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmzdkli.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrytayh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjlrmuz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gopmnzdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqzrqi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtryhda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jobpqazw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mowlmzpl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyunmaag.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhjfgrk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyiijmi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmetwgn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtddaew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsdtzjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsodygg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzrfykp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zmscuhjw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prykkysu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxucebyv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gditdfcq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqhimhd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2txjrmndt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbzmrdg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dosvnwxz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkbwnnw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2usldqbqz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnbwgko.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2quoybtob.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozajbrrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmabtzfs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2joxgmqtz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmxfpty.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oonssfil.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaiifzl.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvczptzw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkutypgb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlvypww.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgminlkf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxrwlk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpvkvay.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoeohyi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqsjkqs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhtjozl.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgcuqfw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfgtecy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxkxkcq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vptrucrc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2abgmxbpf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qthbknur.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjdtkhz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhczplq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmvfmlj.html


<!-- 参考信息 -->