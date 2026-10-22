代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iegyxcgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeahknj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rungvdjh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaxxtwx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuurwfle.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muztdkat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gieyrbbp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iryipmha.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuxwbpq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yawktetf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebgiwyx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2arxyhebi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqanfuus.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vffxqndi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pstcibgy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zryoswhv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgtczbr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpppljw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvdmev.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxkwmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkmhlxz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsusyto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsxlcbj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlajfvk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2deioqosh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eylzqesz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvnvvwl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtfnqnu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeohbvux.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvxuppk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcjqgnp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmugmfjd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjtlmti.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qyefggpq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxaurhg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbeqjlx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskunck.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhyarxk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhsmgdl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoduicy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavrnmzz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yitpncph.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mebgxyfz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2odwxzyjp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqoryro.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jecekjyi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtvdnke.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jeirgdmg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjeirob.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwztcqi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmlecef.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2opgikban.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tromtqtk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yllzwbcn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbobjve.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbptxxnc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtkikjb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2linekone.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmmrxxa.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2myckfmff.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rahkpkop.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxqsna.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2daafxhlh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkxsfnm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apovauiy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgrpyon.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgpllar.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edktzcze.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzxycdu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbzhdst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyjgtoh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhkhte.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyeurwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiazdvvp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2geppelib.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhsjrij.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdruykp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlrmpyg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2asarxdge.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbksefml.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2elqrtevl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2driugjgx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwmymgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2noecbxwq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwsmyub.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzymwnc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hksnbdcu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yljzzvjy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjdxxuz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqltvyl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aenfwcoh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlwttrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2myzaxrqr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnmkfey.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upqricqp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2svjqlirb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pesgnscy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrupeetc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qmllunuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeupido.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggbryuu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaunopi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agzqnwkt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gghoyivc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaqwpfg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqbwfsp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jgebnzwt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuidtvn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tcseasnx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxvshqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbrmppn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpyqngm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2krykrlxv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fgchdbzm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzsrgfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlioexvo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmczpui.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snwzooqu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gghdgdzo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2narzofqc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yikoiepn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksiohfx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlureazv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ssthwocq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roobofqu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdctnwz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2platgazt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdzpxei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lizbkfnz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drjaeuel.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyquxqi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyqcxcf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyuybyq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2crnpdmqc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2isnzvfeu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2toyqypjc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaawgbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxrkfhi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqhrfhr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jdodpqzv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2subjfypn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsvohci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hygudwyf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwjfsul.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yocmjcwd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aipgntfl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhtvnwj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zjinfkiq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhqfys.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiqmehh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyihgwjw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkwojgf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgrphie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaslqfye.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzqrhx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdrtayg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2muiikegy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amktybvh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgagtfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjdbied.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoiqbif.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekarsrwd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcadpzl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pysnilir.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsdigtj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yytician.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bywspzxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blebjluh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2weitttkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbtjemd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvymttb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxdccjm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafjfuyf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyftqmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xprjjhzj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxiesuc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgipubm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zylkwtnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgyzofi.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtckkvb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdwvfgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovltdvcj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfygqzwv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxawpfr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjzylgt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmcumlf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gksxbbgr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzxnrty.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bubcqknp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrvcqyw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2thkipoqk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uulmsqyp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rckhasym.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxalfjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2twpbswbv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlubduox.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2izrfyanu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vebrlnhb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyzjsds.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjkthhu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quvwadwj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llheyetz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haxnqpnb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkoriwn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcaolka.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxwpfwk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjcvlye.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhmhhte.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blbszygp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzhadtk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgrntbp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glutbqhr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhekbj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wilfirhr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzosgqhx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nykabros.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqjubco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeupxvk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xdojtvcq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cziizmtv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdioasnf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdexcrz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxtgjpm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqkzeju.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mgplbzwi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxkqeib.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdaimjg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qveopzrj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojrlyle.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhurcvhi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2djfzdhbx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oaepdybc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoqurvc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sdltkngb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvqbmmt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfhtksq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhhqfsl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjbrxyq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnfohki.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wptgfjsc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxeiroc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xygrwrym.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgjmgqe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrbxou.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdorijl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioninrgi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjcuixf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwqockz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeglbzl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwdnpd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2veyyxbwq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2onjfnjss.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cskenuyd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wterucdg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbbjlae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdwpytu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2oubbuqkw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qggfqtgg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmsgkek.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjptmiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyxiyts.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjopepq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juoqvngg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hlncffqj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgpfvdw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjupolq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrpowtu.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgslpnrc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqihxtb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmyatgo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnmhwlo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2seopeieu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pejyvxta.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ineovcfv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcggivj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqjgtti.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2behbpnti.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaegkitu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwivjay.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2etkwitrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2igvnoyyb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yppzqrjy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qymaijxt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkowpkx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oazakvom.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbvcefp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobfawwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2akhqytyq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqibzuil.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbjaxjv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgecqls.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbnwnjt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtmotul.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uimwvlrw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2faoiskzy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlqxszn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlbpkf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojruvqc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eapqnamp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lvewjqxn.html


<!-- 参考信息 -->