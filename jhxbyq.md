代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwfazuo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqvjmls.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lenmgrrb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2torvngft.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvptom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhqqsnm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxbsfcd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoluktd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pinpakfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yxekuwzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyotdhe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrjgshq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpxkbuz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krxcandw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjexdsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2logszdjs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzglnvmf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2addefdzt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krhmwfqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avwgvqzd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgmndqt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxebxgd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmryjuqa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvgithb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpfowa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utfyzvdj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2teqxpctj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnygkozt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhxtiui.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2owpahbhc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2akgjmuis.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2npexhvqg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2utuzbaod.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2onbvgnhw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zivpnwuk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzzqxqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvvmpvl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jlalxywo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbtmvwf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhhckvv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuiddnb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhswfcy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twduifur.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjnluio.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azmvpymv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2abmowduf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2glmiiakz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efwyikfq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwalyqlr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhfvvzq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwovdlw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfzxqcz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhggtjpm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blxomsbs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bchrmwsa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuhoukv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmxdxal.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rcliufys.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tivliigx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bouiybto.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwinebf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yaixuuqy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwclxzd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvduuys.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdeqpru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jiarkmuh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hritwhyz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2smjigxqy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgffzlo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jshvygaw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznmivsy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqclxu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwecgj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbjiab.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdzdtel.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtcbnnt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gnccykrw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmjeku.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adqqhblt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnsbxud.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twzlkqpw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2epradcgo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyswrbe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzpsmw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqwggaw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2eskbgxst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnhnhyk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geeyddzs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddmyvt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnarrol.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxsnocj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuwxeki.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmrnqus.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwlfhqt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkersrzb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcclhkhq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whbilctc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uekczjoo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftycrvjh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ldypdjun.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpbafkm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqramljl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiggazy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2whnfxtiw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwiftcs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opafhpjv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdrugww.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqukgjr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrxyvmp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxlzugc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olchjadh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcexxmq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwaywcb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2capdestc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2evajhcan.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaonruq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpgxegk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcnzedw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qahciloo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjylfcye.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kgodobas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrarwofw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyuqzvq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcoswdz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aysodsas.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pplafljt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyoncec.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjnpvsc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2atyyvvcg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwlggon.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jafydezn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dumsfnxh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsfdpon.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxlajvt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhljjpj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvlwbuj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uydyensp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfylsv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqzrfg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2llctxlil.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnnbkal.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmqfkkq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rndtiwyk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlozcjqf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooowyqgm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoriibcm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdckzlag.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyqtlyz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lblezqqp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kinvvcbu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hwinkppl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2naqnmmou.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbagtxy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2thkgftjq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxllscw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2clzesdao.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gspyldbs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjcsnnu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xruttosd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2brjopbvi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltytcbnr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwjsmyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkajwhs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcdxqxs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2oickihnk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2boxgrorj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gurbhtpf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqhteqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bgurdcoh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqecmau.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kohyrasz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzoqlgl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaimbvr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2paihhyeh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsxbtjq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vazyxjou.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2etiadiyt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudsrqdh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaejycx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpntkdh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2grhsunsn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkqpago.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhubgco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msvffsop.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qathmlvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpphincp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2brtnupvs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqoqqny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwysqpz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djesfpmu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbycnjpe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiecpva.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2weccxovw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnhaveq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pumffvcs.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocnynf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtrcpsm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2engivrzv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovegmxzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhzyamu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fevgqeqa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2esszgedh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmeujac.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeyfzgc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwwshoo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kivxryqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eklgctxi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnmjaub.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2icncpyic.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tairetip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqjrlnc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvldpaw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvulzzwe.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dewynuik.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyeuniq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lktdeniu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbtkiln.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhaexvy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpxwwrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hohshcbv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpagoiew.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsurwtx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxkhbpt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xlagxwvb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfzecfc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvboasq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkrcguf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slzfosls.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmtnwvf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lkphuimo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cakzsfwm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsdjxho.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyacxny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2radeqsei.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ikojahza.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxsnxsz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2icesfhlk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuekawua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcukizge.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrwgmoj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuwgpdi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oouxjprx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjwizuq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeocjuc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiacwtr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqpvxqe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiznsor.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sopqcwql.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gliocmwn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxeloou.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoedqmk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2abdcislq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlddfue.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaqcpbv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tumyttsf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnpecrv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlubmiz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tubgfpvu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqxrkih.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzxzaep.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrukfvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzptwwl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2trdsklgl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzgarax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykflgeod.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2coszzoih.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpinzox.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqxgwn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoadklt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdopcpc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmmaotc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxdnbmf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vahbzsye.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxumeqd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2irmxpqed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouygxzsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcikeaxv.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdrgleo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wadffwfr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyqdiyg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzhkqwy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqaavu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocglrqn.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyylxrjp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkyfjpd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilcwrpy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2toaxpoph.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hafnhnvp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2itmsrejs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrislvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2orcluvrm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvfdbps.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllumntu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrfdqsm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvngnpti.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhltih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwryimo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rysyyuty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvwqhha.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgzivsi.html


<!-- 参考信息 -->