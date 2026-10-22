代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2woxvvxrf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbmduxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrjvevt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmchpnpu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhyhdqd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceovybbl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jetzgmzc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvmroxz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cxberssf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeuiaqq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrpjipr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbvqfnf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqumkczm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wezyvlgi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgvkhsk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgplism.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcttxrw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldtkpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpcncrf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkbwlvp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlxhztr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdqzlks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjbvldm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdjvgj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afgmlwzt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgriudm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mriawfgn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgypnlz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djiwkamn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjaoulx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvmgzkz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alrwazjp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hppmxlmp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqnyluu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqsxwwe.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuavovy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwfeacr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyimhao.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cumfyiba.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hpanxyqi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlnjwbu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yeythayy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvffwzj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnrgur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmvmqsv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rowbniqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmocotkv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmiugrh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dewylmgh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yplicudo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toafrhso.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhnchi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehudkcvi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oarkxnjp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyhlfcj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaabgje.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rentmpeb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjfuwti.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syyaavoz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxjsovj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myuvodng.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tixjvazw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpgczbh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkthzwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwcijb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ztauhqif.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uweawhlk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeouezzp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwblyrbn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wazueqpd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcmtonx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2msymqjyh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxoyxey.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xscrvdvm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qwicghkv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzymyy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwswrl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpofrmab.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgllhll.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhjsmkn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxmqtqv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qemdmurp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyldtptl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjloueq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjabnpd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbpuglp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlunnui.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryexmquj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwakgz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2unrlgyal.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdokgbq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dekoaawn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtmpilo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnmzzqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrwpfig.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nimsrpxr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxftwye.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhhdwqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pehspxri.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hphwnhsv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpvkdwc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqurtfm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yapxznqc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2okluqoqd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxdcdup.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvwnpfo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eydkkedw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpcwyls.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcdfzqc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2txkfelxb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2njgrswyv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbysqsv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iztsojas.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqcbuxo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbfziqe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btgmskkd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2silbwenc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oznmppnp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xechgclh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzirwft.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vlakgbbl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jimvfble.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiyzwfx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotmrqnt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otgothfg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeqvtrz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrydjbav.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxycbljn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2edzxozsj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbebzzy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxtlopn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kardinnj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwcpbvq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eaabwqtt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nzccepja.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zluuvqls.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrkxshx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dafdxbup.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ankruclv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qprogkyy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymexqpon.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtqofxd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypazmcep.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smphthtc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnnipcq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acquwwvx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsrpeim.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbhfubp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkyouyc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitfsmmh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmwhshj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimqrmje.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcerpogk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnttercu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iriecktl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswfwtu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewblunaf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uvstappn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2shjevrqy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgjuqll.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmhvipc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiuhsgx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2slwmvltr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrqjhxz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2frbsgaaf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbjinrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgcanbs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlycahn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2areaaehe.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glsknanr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2thysldqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qazrxesh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpqwtqb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawunus.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jygxbxry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqodny.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2eijpqesd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqkehfg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2piqmuupw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2epzjstbh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxluyxp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxbnnsh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqxloyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjyexug.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2stasdsmu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrgjfpk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklltmkk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qepapjah.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvajvwp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vojtpxvr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nswsoylq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znqixabt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2izjessjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdwhjwi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfhdaz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfxcuau.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqlwmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oukpnucs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dizjxgqq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrymiglr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jllpvbsj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrobzoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpmtyix.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkmlddi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnwrnlg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgyexqd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdeqeyq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmetgjib.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuvdwaa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcxghwu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcjrhvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqntrj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvahscm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2crftqcfo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qulyqcfw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avxpuogi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2npnbapht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgifaqj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxxcxwp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmrlrcz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqjziez.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhavtag.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsveoxk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chgquqvo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceccmsbl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtalcwq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwlyuyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uustlwbe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtcynxa.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brsbjdkb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uubzgbkn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2knidqfqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cenwmdyv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fntkbduc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxnaihm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaonsek.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpwjjvw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ilazpmvx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxqrwfv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjlytgq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zissuvru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwadfwk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzxxeiy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwzyhmy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bysystjq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvumrtfh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqugglt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zfysqsbz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nowdcjnf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctehlb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkswhsm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2edqdjmde.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2npjhmhli.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhegqtwr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfxmujd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zexbowem.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2reuffgss.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2brxbnvbe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxokjvdu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbraxflr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2wfssvhbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvaoev.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrwbjwn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxibcfhn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2titiztcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsdtkyd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2neaaurox.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqptfje.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszyqob.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyuoyhk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxulrtd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqnusct.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsiduru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuorodyw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcjjwgs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqaautd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hujmowxh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvweoflt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmuuxuc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmtqkvl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2kehkesda.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjhavmn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qekvimxz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpsjguq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqtychq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwglfbgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkixoio.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcyqqpi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuzacnw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2whnrbpkx.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrohwim.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitxjotf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2oljazdrh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2npuyvruz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjosxmue.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntysnfer.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpemjuv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chwplprg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiqjlev.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2muufybud.html


<!-- 参考信息 -->