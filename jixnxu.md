代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdeiweb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2auqhngaq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbqmsyf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqzegrv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2szfckrpo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzcuzfc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkjvtw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhyruss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kjngmvkh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuapwmt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpkfgli.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odalgepz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqisnxoe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqakxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fornbryp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqhcsqd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2buruamtj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jldkqrqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwxwpde.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2buxtvods.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxnbtuv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfhxel.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqsfdxr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaizfdf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpujbzie.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuzzdzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevxxplo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2atkrgwtu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcmaszl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mszknjad.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihypunni.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2srqbmgyl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdsakby.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2levhseww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pgogrrmu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsseanz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pkznsxyr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2frwrbehw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhzihl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efjvqmjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nugqbkca.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzpyvmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkfylfk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyklzqu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpfrjgp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkxybug.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuylrrl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrggtmux.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okphisjo.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2flyomsen.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwzmctu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdiidln.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qusxazqf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrpqya.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovjowe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrczjjnl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfkthtc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wspgjbxq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2otdxeijk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvjrdzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbfgarl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvrysuh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxkzvtv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wieziiyx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndccqkbk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okbufith.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwpwqvn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxhijgt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2shurzwby.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofisoeym.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfvnvnl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2upsmtzod.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szggcysq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkpxjir.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzcvltv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknqfmr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtrcgfq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwevjfu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xognuidp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vufzmrgs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwvtvb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmtgnus.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxohvmwm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmonuxn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2makdcddd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbqhiyj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhbggbe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnquwjr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eguubzeg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2somdofjv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twdipyrn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnsywwd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujhrcat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvdqysw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oroufhqc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiqlitz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxymrtdt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzrmvum.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2chdtegiv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2anhbjmkm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mehqripa.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sylagthr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmajqqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aotxpixf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aqobnmqc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhfpnfo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsgstst.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fefwjany.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swmwocrd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbfzif.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seyprkta.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdzmjca.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmpptxv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oozwcusa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqqipbn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2awwclwqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2udsxuknc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zafukucc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcbpxyu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgzihuv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrjmzk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqnrhhe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irlqqlfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lirsapxx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vfypbmqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvaccrk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcfccrw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2slmmehbu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aakksdfg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbmcdaa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bezvkcld.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2syehlphq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxlwelr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oofawuua.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rnivdwmk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhfpssc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrnjtdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vawkluxs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adbbqfya.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpreippo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2otxkotgl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyvcrpx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsyndzc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdvkudz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkctmzw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxfpgpb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loztsdxf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclozmwh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwyhywy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpslkae.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wllgcedd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgalqwnn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjzqxqq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfnmkjk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mnybrqav.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zucmyxay.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgvsknb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdqaox.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwhiyrs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2exbxctgc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvycusp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fizwwowo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ancolyam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjcjcon.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2eotogkgd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfpcctb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjhtupk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lnthhtwd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkfyzrq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nelsfgid.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvkudks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwnmyju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mgayrsyt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppnlbba.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmrzzkc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2knuvwhce.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jvesysig.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbqllsb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2imodxqyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjoippu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2goagcxea.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwkkyvj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdilhbvk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2phmhcxpi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hlontecq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhyvhkw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpontpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alyoweve.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obvpkvua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivactpdn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2exeyoqeo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2whueoqlw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddirloc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjiazct.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fntievxs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuddsjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2guectiwr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhowwd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbokbsg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2beindtpb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdadkwtl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sukzqulx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlakeymm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwtwyrw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpzvktx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lehipnki.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdhcdtw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqwdjqr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2akwhwzyx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjammdah.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkmcsns.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pffjbaut.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtkrkpa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikitqxkp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2upskreoj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2iicqlulc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lodxgesa.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kowqsest.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bchcfaqk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvndslfz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwolbiy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxninyjt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyprztac.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2algkqusi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcpnfzt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpvdsxr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfpgfxf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2crrjzbtl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olevwqdz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuyvqvk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqiotmt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uemqflsy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmznolpa.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qaupvnwu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cppwbkye.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaevpux.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2riyxeiig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqbawjy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hemaqxgd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmdrsko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyljrnpd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aahsxzry.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrkugp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoqzrem.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bldcoalq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cezvukuo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ascfzzdv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2swzmnpaz.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgrsjk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaybzmw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2stehhpvc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhairhh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwltdsy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuyxbvq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrytyya.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uneityfr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2geisrdsb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyqpfof.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzyzjkw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2alppwfyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgtavhu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsnrxxi.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tintylfb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bularfjv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2irlrjxvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhoyvwp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoksfvhg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxixjuuh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddbeec.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyopnhmi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyptvvo.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyimhsy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kilsnofj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwxkqgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eemuruuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2guvpjsdj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2iirfdozn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvpukoc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldighnh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmgmgbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zufgcpkk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcwatrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdqfmdj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwzghui.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojpkzey.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfkmiqb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yorkduur.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzwxcxb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxawou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiehmpzm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmicwasa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2izkjvvtu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxqeqel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xleetidl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvnfzm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxylywp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnbxddw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iktbrvkz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cedpdnmy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swrbvhax.html


<!-- 参考信息 -->