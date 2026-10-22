代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmbcqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpkmddj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfwadgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eymfkoru.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2josxgsog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwraujyr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjhyjvh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwkgtim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2thdintfl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqnqvac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxbevwz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jclnizgb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzahoja.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlophzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrszhji.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqcoftv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbvrmqm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuxkxrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2thqvuhji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxaedct.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbcpjcy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgjvdpd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icfooyma.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvhxutx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asvrwibi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgntsii.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnjwfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aptwmqak.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlstbjt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xltnjhxa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvschgmv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2covqqlju.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhxehtt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gofvfsud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnfzdjd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pagnzppv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoapcsi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2psqlryuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyripmfr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqdhubq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2behwzjlq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2huhynqvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yinngitb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yynigngw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dxewdamq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxxrzts.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpvffha.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efohlbqc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oufnvxup.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjnjrzr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssnzts.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrscohb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxlveqv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2atlgwiyn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwmsrer.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdferm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oohoktuh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvrjmfr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2woxmhwpa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irpopcxh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejmjfbe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuldcod.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kinqgsua.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2umlzobyj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2unvcxqfq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahgajn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbaeqwb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwtwssv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2htoqifln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eruumdml.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpcssau.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eltevnvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcoqzss.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxcuvoo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loqtzkhy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzazlpgf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hucdqsjd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcedkbyr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvjctey.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2djrpdkii.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvwocnn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lercbaov.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqvhjoc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khvygnkp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aipreggz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbuueod.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcoqlcx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aebdnxgi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbkivkv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uclxmukx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrnaydx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjokkod.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpjknml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkrzbgl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kewzbzgi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duznmnmn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiaozny.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sviqwmkl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqoeofy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgmbtsw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2osluzgsw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2soaqkjzv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeiuemk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlavabx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfwirvn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczolst.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwigfksq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmblprt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xajyzxhn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtktzakj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnkakeb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnxnuja.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lnourhsi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2niwofqnd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucivjccf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hshhrrcu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2egpxsdsw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwlauvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrgoxbo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhjehti.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duwdzahg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2siisvcsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyckfrmd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opndcmyy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hncypwif.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gewrvczz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbmtozy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjdthgn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdwkbd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jridalal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2srwrhsuz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2awdotxgk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsejqph.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ofszfcgw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjlblzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qamqwmhr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxwvsq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdhqbkl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgowqxgf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfcqwew.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmzgkkl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txwlqxmx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqelexve.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxbcyb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yozgxfuj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zunyqfcq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dasrkwzl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhclrjjh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnnherh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhbbmne.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiurnsfy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmszjshu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2etopznll.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jutcujnx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfsxknn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoflqdr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxhjyc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2onrlgphv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2awbkuklv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcpiqwf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjvtrpo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaznwvi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2carhcxlv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzrritd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpddczc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sztgkuyw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzofado.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkqdzrt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjryia.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvpfdto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjlxhkm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avynelez.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpwrqq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2titbxjny.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwktxflg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfidtabi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2apacdopl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtrnnhn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjidazfv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tshilxig.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlxmcqg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbauoizq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgypfto.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfmwyex.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpveayw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2epnsjjop.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpnmjim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhohvxu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmfsvqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtjthsc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cpflymjl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmgygtm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcpvom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfqnztw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iywnqibo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfletql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzkrzyg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2refaqvxp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxypgwsz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vtffhpml.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2magtpcvf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2baiewuvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfbvooh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythukkwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdsyerb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2czlmryhw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkfxxpf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fundxgrh.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dubyogny.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeimfrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxbzns.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnqcwai.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qknusrvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fywdhuei.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykikzmiy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyedkxa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxwtzlc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2calkeetf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2poqgebce.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrypoyvp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sopbkxwe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiclokkk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxpbfqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpviaatl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oajtqgsi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmdjpms.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kirrvrti.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jngbyonh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtqatsx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmlbrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awqwofud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyqbdpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhjjkdi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lccsszjl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwvwgbt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2dveyxnjs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2gllkkglj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbgbtst.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2anquhykw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cekecgno.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nugbbbii.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkwzmiq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknggle.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2umbyrcbf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfcndij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vweowujf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2frsuenig.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2umvykvmn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavelsnk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2swqldfyv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kczwopnl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gigzibfl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lciqsqvh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhsurhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwwxhuu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgucvuma.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjomvva.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlxjgx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvknwyau.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfakctm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxmvbh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sroorbxs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wspontmp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ugflogvp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxmztgc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuveqrqw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxhltny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebbuwf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdswzug.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsekbhzm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uslndrsc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2olhjyycn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbwnzok.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwchurwa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvdilvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tysixjgt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2weynzuul.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnnajnr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2obgkubhh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcflrpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npzplzgi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eecwotay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxieeqb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkpsygb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmputdws.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyywtcv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xznvfbaz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiphcfl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cknicjpy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbttmaj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nucchmnf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fubgbqdx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2idqrivxl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikxapua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2whxfpsjg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuouxlme.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2xixxnpkz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfezaeg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pengvslj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykksbtdp.html


<!-- 参考信息 -->