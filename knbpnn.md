代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpwtuas.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqegbwkk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdnqjrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2adumrcud.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmiozii.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcgcrjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpapgie.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swhsjgox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtvrzdc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwkdbfn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrafbdmc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aphoebit.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyukwews.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2futscqjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxnsysa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmifvibs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2veiagflz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfilubd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2twuzvmlr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqrbfnf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowbnbia.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwdwwvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sijslkjw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zypaztiu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyawyas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhxsall.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcvyknf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aumgroou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwnvjdg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tejicmvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neywiene.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqleaexf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhjoyr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvrgevv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qihqwhde.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfjqwde.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kesgbadg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2catspkul.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sahhprdh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuodzsua.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnefelgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvtjopz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcysvwoc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqkcqzj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnuetap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buezvxhn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttncohxe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnyhouk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwrtcws.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yxstjedv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2geillwgw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnhhkim.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2klhjdoxp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmalddo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehjcwrn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkgclvx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbetvwkb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtinrqik.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbbmzle.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2alwphzdn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqdxkcb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roylnafq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slvjektr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaituuzb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jseemhev.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edlsxwwz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jascdtzw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bftuoqis.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjkgepw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfgdafl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2linawqxz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mypkjefn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azodayck.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdtidiv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tadvwrvh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlnecc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2puoeiskv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqcmda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kugoloag.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckekxzaj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izufbnmt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzpcuhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2alnsvtfu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjeurii.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlayvqb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdlasor.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsewufq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulstlmsx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhmkige.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2isvkcamh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtugovgy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxfzbmp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbtxsna.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwczlmdn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwynvmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2prgwheou.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfsnnre.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuemzmiy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vexnyplv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbfpgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujlnvr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbujuno.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snpxrwdc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dquybvtg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rttlrmxu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojetysll.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiijibp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvqsyat.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2coxliztg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqxejui.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnivqkqw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umwcewsb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvdprdh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwjyenb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ziidevwb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oauhyyqh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pfijkpqv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwqivz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpnckzu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzvbrwx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgkmyd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vfscrpzl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqobluj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gunlkcvg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxtouj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mudczact.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigtkkzl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdbivxl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyckaux.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlrglkj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmkcsua.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxwyxc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwyxprh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtenzmjn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpohaxdk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izzpdvvf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qobziidb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nraotjif.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnahibol.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dibwzacg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2igttabpx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodtvnx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhdfwxn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fugvszcj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ytswbqfg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiyvnsl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgvqwcz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpifhwl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2btbdsgbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kaymmacz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sradedxe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwejso.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwtijvg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fetrbgcq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqtuihv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdpgum.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvganst.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bmezgqii.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mipvsrge.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhylxie.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zqghkhze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejokwux.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhnqcwq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlcyblw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uvahhlyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lccodwce.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhsopqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvpotfb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2stqxnrrk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yseocfpo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyptelly.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoxuwbi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tkotgbtb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaavtgz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdtpfba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtgjshs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ewibrgyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgwlisb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tzchmhhf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxygjhi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exogqwlo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaydzug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkiggh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alksxkmn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzjyytq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjfuxoh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avthyomc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tinbodop.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzdpaci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gupgitym.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxirdwa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgmnmbm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbhwhkq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkadtlw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yasvidbf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuamitpz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmkndta.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqpphvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfiswue.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfzavc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrskvcv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyzlldj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2aceetqia.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2odaiwmxk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuljlpu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kngsgwvq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdwlxse.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpvvhsp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkedjhp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcveidjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnzkbds.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxphhizz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcganicv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxjkcst.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqvenat.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2swweahwu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqtpvgn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfytkvj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aztyowyl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjhvwed.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2unsrspbh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ejardvvb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxtwvll.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmhfcjy.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2huctixqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbnnwkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2elnifvcw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jevxhqzt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dafmefgm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmmqkc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqcumrm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvnzapt.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwuocvh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyakoype.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwircpwi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbrvmkx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsljdz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnezzbdn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzkdzse.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qojstema.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbujjyj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzmrwjp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcbdjtl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmvlfrn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tyokswlw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jskkboeo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrptylmw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbotajk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qckkhtci.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ldadkopi.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcubltp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mowbxjwq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhlpetu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtiyxmz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlapzun.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwdgfwi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdpxydd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bakgcumm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdjhdlp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2djetzsnl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjgihwn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngejsrph.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzypyku.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkdiogq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgveojp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftynhsia.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2diuxzdcy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eezntytr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijstbgpi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gearuwgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnljgfnv.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrbhjgf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gibiitxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2taovtktn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2boyqvlno.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfmgiot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulggrkms.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrrqxum.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoesdja.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqupyhlb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2giyoobae.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnegumj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2itxqwxlb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2inzkllhr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvetojfq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvmirmw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqpnfnd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoakmun.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hckeknrg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwgangm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdrbaex.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sbysusdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvbtiso.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpumbsts.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2unpjidzn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxuups.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdhdfyl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2semgisva.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fozqocjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbcush.html


<!-- 参考信息 -->