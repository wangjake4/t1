代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdkganz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbmkfna.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqijhiif.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2puzwqczf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2clgjjpof.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sikcnfjw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2exyumdof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaviqhl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedhsru.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhzuych.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdkafdq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twuxsuch.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oskfxozx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgukhxx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wztoqbkg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmefavyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcrfwyj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkievo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzseckr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeqqnye.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjydecrv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpotexf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuebbfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzobhhdf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndknzrto.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfzciuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cttxtnau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srdvjezg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mghacduy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krbgpbpf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fstybbwq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkvendz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnntclvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bhokgytg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aahijoof.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjnbwtm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2noahdfvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2znqdcdny.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmicuhbx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoptblw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etrqyzcj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2klndwofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgrbpp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbmmdua.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2znduehwg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psjkfvxb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okhqvvca.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwnlaa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaffqvfj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tebsvslr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ashqiade.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkzjxsv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpixchn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yssuxtho.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khvyngvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgmstky.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeakgpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispnfswu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiukagac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odkyxqti.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhnvtyi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdhgvvw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkesny.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vddnrohb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tipvffaw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfetfec.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2glztvqps.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfztiln.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkynqma.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npxaazcg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzryhma.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbewyth.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nooqammx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhsghgk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lparvlps.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvllfyt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2biouporj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwagajqf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rifxwxus.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdeszqh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunhpzk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usaagggs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azreupqg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djwiqmkn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htwscsfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iysypars.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkjbzav.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtanfwji.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzodvr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrcemn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fioaaeoh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghalypkg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvcdvlp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2initsebb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kksnyrwy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xutmnlpf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkognsrf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxvqohi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2isqubqch.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eguwgngw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyklompe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xontxpef.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxijtgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2abtdwsbs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtxcxga.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywifgvyz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zplvgbrr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2eyldbmik.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjcbcqd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykworxdp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhksttcs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfluqoon.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gszopaou.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egrwmocz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aanjrdus.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeoxzeh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmnsytb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxczyux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bchdolji.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwedfl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erawpcod.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmjnvje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhikohv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2loczfvxn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ubykrdyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnimytj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xqemouvj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbdtli.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lenmcjuf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrjxfua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkerno.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwjhehn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpcqzel.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2boxftvks.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdjozzd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dutjbbcy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaleswiw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiquond.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhguelm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kahcjqsq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2olqtjnrq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwrhucg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhlvkuf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cgflhvrr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2untaxlii.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcvyqpn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sajnnzkb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpktlsg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzyjqv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfartsv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsycgsl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2usvscxtf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzprmjf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2scnkkgvg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2htfyrzbm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2szsgyawl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wzigptis.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxwuzpr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihyuyav.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2duahofrm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iskpdhgq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2usjxzzgm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2edqefnxp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbzwqdo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqqiwlx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxbxkgb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wenstefd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpldxsr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmjasaq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hgairagj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2okftrbtv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxjoley.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2irusrxny.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okzicwng.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxisvdo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mghutrut.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjmyqoy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbpgucn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2plalfvon.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tonogbsp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2upxkohdk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmuincv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jovnishc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdkbzgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2chskikxl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcpmbka.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkhkeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbryuid.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2layehxfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqguygtc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjrthsp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pactiipr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecdoqkf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngngvbnp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkrbqar.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkzkrmr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlznrep.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqlqnya.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgovidd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhsexzs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdjjmmo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqziion.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgptvzqf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byfjtofn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsskfmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dowplvzk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixehratr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipishqai.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlwcccl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwafxco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfmpngw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cazbpuhj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkgitpv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cisipmar.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmoistu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhhmqyj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xndykfde.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsqdbpt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jipcewba.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzitlpt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuuozrx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqzmalb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfsvudb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2omlzhhnz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ralbpswr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naostrvh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgoqghp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wswbvyyo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqghviwj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbirwiq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrgxlei.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prkrjcux.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnepbvm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2bskwotke.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svnqotce.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeemxke.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnhndny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2akequhye.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjukbyv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mmideqtk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2eboxdezi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkqwgjr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgtlfrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwzopcz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qbixmdgq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhiervf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yohcdgbh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvyucrp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthjesjd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lixqweta.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eixuccqt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyswpxs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaaomja.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kislwroo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2sspmehpq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfdroej.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rawlekeu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryokxhvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvynkkvf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkckfsr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tnycsnie.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvgygnr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2otibysub.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxzokvp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2riptdmot.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjukaylm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmycesef.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2falztydp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzrawva.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bluxsjqg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2prpkvwed.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2puiifcvf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycailepp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2tusvtqiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsawas.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2exjsmjxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jlboszci.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfitnhmj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2auxcaalw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgipcfui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqzjzo.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kebhvexb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvabyak.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rztdtood.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvwfzye.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqnccgk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtezklbg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfffvbvz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavjfba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpnawup.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycitsjlt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdrsblw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2stcdcigi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqcpqgw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uolbilwo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxmrzyq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngneppgz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxzlfsp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zecsteei.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwdwlis.html


<!-- 参考信息 -->