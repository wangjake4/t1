代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2oewjmlpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esqdypps.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mguloojq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjfique.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvtjer.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2falrkbev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dizasnvi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxxilm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ummaaeyt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pmamjycf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgilljwa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yllmwcng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yralxjtj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2htehbozb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwisvgum.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfitjehc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjujsvs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rioytirf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyywadlq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpquyrwr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkxofxm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoetpjhz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhskgbt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmysbpi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blkyarws.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gkksjcjp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnigehn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drasabzz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crhtgoel.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlfvirl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypyqdb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtivrbfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxbtsjf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2awvdhgec.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2guyaeegz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyesfaxn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxllatzo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmbcobe.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlqcvah.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eumdgdsi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjjkdsi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2csyfzjrq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dqicsvqh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2waxyqqlw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxjgkfv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmtiodd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffxrdcl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crqxqztw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nynugopw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwydxg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrbrdla.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jdogtsgq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqmanrz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwgwpjf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emddzasv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfsaulh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcyqkzm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uoehlxmb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgduclt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgfslpj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcflkod.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcxiyxg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbywgj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhonmjs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpklqaxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzmsitm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qlumholo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqdmots.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gevbchmk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oomkvhxr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhmhes.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrtyqds.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pswentni.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeooctea.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqzfmrj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcxzzvo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzdouae.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cobomluw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaonzfb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2chviuvbf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdwiaei.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtljvuav.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arighklu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okfeepcj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2agksoklb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmljaopc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qieveqbi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlsrowg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtramfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdqjckf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ahilvcpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvwuhwn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtlseap.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcvvvvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwkmyd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfoxfva.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfkciin.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzkdhxz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zayifpsc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvqehgd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmmxmal.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwubivq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2axwsbbbs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sndirunf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyimbob.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iiygfwtm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxkcfgi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotifqhw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msymsnfw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglagfln.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnsirfp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bukhsksh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lreemopn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cshusmzy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2baxmpnbe.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkmivlt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvroklok.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgsriob.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gobwrpfn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toqkpphx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcurxxaa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2figkwsvj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkncosib.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcpbcwp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpnlzke.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rjctiera.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqxuada.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoujyfu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rlghjhoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxtlhyp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pduxwuji.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2togthqav.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgklccb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdxawza.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2voldlffy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bonjziqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqoffup.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zriyneeo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkyemax.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgyuxti.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwaxwkl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrwmhww.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhwgbse.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyptwul.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vrynchuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmulbxkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxkuloj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxvcgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zsebynke.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sovmilmm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjhsgda.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2flxiwnsu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwjgprk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2izyqgfrj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxajjhkr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeefslck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sfelgtfe.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2myonhvbc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhzxtif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuhdqoh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oafoeloc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdddlpew.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ltevkrok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqyrefx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdhbehw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhumggce.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iomixebp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfilyxlx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sahnsmww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqtgvcy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fernksxl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2thmpvkbs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zywaxqpp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslxedl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugsepbe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbcoyfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlwwhrd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2thgpnoku.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eotsaoyj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bepjytik.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgtpgkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2frdquezh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nllmewtk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrvksdg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmxtsyg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqcoluo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhnjgn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpulkaao.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnhrnpt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opukfpri.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tcinwure.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eatvedyo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuliawo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpbccfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alqjqxtd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygoekpd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tiprwqkx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etvjoxym.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yauqvqcb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmrqhok.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsskxnb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aypkitrb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snpwchwp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbunokd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmcabnb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nzchnpvg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnwdnsj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ivedjixi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2shugfavb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2spbhklfe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rkttdlto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ttverwuv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwuyotn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcihfor.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagotceb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhmeplu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uegsncvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyppxeuk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bowtgqkg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afopzzsd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oolarxxk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xemwbrjp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rzufyfpn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2spzaskfl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxqszkx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2onlucqmb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiyyenq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfmtjrc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnodvlk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzafwnin.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2egqzvilu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbwrarc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2idvtrmtn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sapiuoad.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjjqsmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2isjrelsm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2knaffzae.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzipxgtx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzcczuj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrwrgzd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2covedyhy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixapgcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqnxbir.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxzhhrt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdhktie.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2aycmsfom.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzgoss.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2znnnmzxa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjnavvw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwpagps.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbisrnyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lylpycjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqwrolw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkekao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2punljcyd.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeyudqk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpmgeoz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgphnqg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqjqzdq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhaamfd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2peolqoor.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavnchae.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hllqlvao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrtobjt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yontvwft.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grjeevax.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qksdbhgn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2istlypvp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2epymylnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgqsidc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugigjlx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoowizn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfznfq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvuctit.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtsxbdq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcatecvz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhexac.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iiouetpk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2benkszyw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxnatwo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxlmkyn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yisoelqi.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhlwzge.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whsekxmk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aatzrmct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wufvfyex.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsiaioq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoxeday.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhmjcqn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgyjdjy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vakrmjnr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcovuyo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbvgcah.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxfjmpf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdrxfvr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihiwlwy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbmpvly.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtbutmv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkuuaee.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2umizeojh.html


<!-- 参考信息 -->