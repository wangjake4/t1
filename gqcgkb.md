代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqikbrkz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdcbmlr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2scuufmnj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdkacci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eshuyokb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwwhayp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2goanwvhg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyvnofs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnotonh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eujrwrhm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcnryyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gkupcdyi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtawpsl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cupllqtk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcdunlm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peghxcwc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbuysdw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2puyijfhy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2didiymog.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmtfjlj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oouoprvs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qevhgeec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2litdlryh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttsmxz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjzxgml.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkkfacj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxuzie.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvvgovg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgomoiht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drkzngpw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzhizhh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bditrwtm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2flptcsvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhwchyx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjubozvk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fobzkzig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxvhvei.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2shaglmhz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqbwjzs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2avplksnj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wooulinf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqkjgi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhzxpze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uphjywkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvrkpdb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmbrnkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qchmukrp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcroqie.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2apbvfnsx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oieshkxc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjoffxd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwsrdlu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgrhufa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqpimbd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuapkou.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcostgiw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvqjfi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vyotpgpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upaiwbdm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxiigdp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnvhdzl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcfnkwe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbjocz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhgujps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpvxopn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hblkpljw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmishwg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaavkshb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yelorlsl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkznxmyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgzyewo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ziibsmxt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhkuzlz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfxfbui.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jsydsxjr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfqfswv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbkpdji.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqtsumk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhebqcmx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqacpoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xefdmzoj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2avsjpgai.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgerxlxo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhvsuwz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vfohnjpu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtfosza.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxxldkw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kouqlbyo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vufqkwza.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2idymurla.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wasbogya.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwftkic.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2placbqbj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezghkrkp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjquxspt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfkioni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awtvxpgq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaqqfyt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2actrlmle.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mahnmsrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijulcpmr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2udejdjoa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvmligq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdjcbeo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjbwyey.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvxkyuz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sczzhgib.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wanahvwh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiebnjk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eynatqiq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdrbsjc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgkwro.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xefmmima.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qznovjni.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbgouqr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdywwwoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2unmepuhy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhjfvib.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jutebari.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkdpyzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bldniymp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvbkrvx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kodrzrmx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwqnrof.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyywdeph.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdcoofq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgtsuil.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpgohcy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2booetfgl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfncguk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdbnewo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjuoqh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gszhwfqb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdzuvhh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqxjgnn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yudwcclk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mptgnhiw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tyisrmml.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jxehmmcf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anapszjk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbwjyrz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgcoowo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqatxegw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jilwvwdz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pilkykpo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnaduuf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfxevsj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zkovqhts.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlakddad.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krfkbrzh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nirgfanh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epwhtpwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyakvxka.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvaekuj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2trbucbrk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqisbse.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwpxpwv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unhiwfma.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbaxiwl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xgytazrv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2irchfsvt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmftxg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwigxoiu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfcxxpe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlutew.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzsqrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iemftrfo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxchhbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zipjdsry.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzczocv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqngnhf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjomfqi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkaryrt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2caxqsmdz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsahgzfv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inshjric.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2egkysgjr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoghctox.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuezmnc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvtbfdi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdwpmvh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspmbxbt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svrymblm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tpochqew.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfihlsal.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlhprto.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzyrkbu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgkkqft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2inpzcwrv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgzoubu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqroqao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyfqupj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuggifp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mplmxkmt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ozczsker.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2puafkjfd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyibycd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iviqlftw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rafkezgr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2josstafk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gkegpgss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxipmtuy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saduddkd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkzdksu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqxrlgx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuqkvin.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isbzwmup.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwstvmk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nercvbha.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjwnbja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdustrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zflpaqbo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cucxatin.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmobwgmi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aujbgryy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vravrmua.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlgwowv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuzcvfv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgwqakv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxszuaqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlhnwyy.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uukcwbqk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqcwyrr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfrfhkc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awbgisqe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzjxoop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wueedevp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmkpret.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyvhdah.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slnofasj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtorzoa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlvzafe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrgzruz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuccpvg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjqjqrf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfiwlls.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvwsvlt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gpelqlhd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxltafd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tothnhps.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xaalhmhk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtldbcj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxuyvkb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jeietkoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nppmzgbm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rernzbtm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdifbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyfcqcs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2glmgvfnt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfaxvyt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iapfqnjp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagvrdqp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgglxnnn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qggehxue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wemeucmf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hgskhwlc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqekmx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2foqptjvm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlvehuq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fguiueyw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qinebmli.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqotgdph.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbnadbc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dadcpvzn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgjecla.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeoqjrd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iibamnbn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qopsslnn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrzeull.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjditbg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jscqirwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sawqjigp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uubiuzab.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2fflebhcm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgvqvau.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxwdxvm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2lagzbekh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjyorxr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ikisnzix.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuxibaj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtfyxnc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdkibap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemhryza.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfhytg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfmbdek.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2siqlxees.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cenwoygz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wykoszwi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpytvdpj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jamebdeo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypehzsm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmsszqk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzdxjmz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2crestufj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygbrueg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2leaplnxe.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjlizcm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvyptrk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzvfikr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgulracr.html


<!-- 参考信息 -->