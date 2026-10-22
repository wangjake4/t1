代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fmirjoza.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqicxbry.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yotsqlaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2govcxxwn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqpeizq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzaeyyv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mylimhxv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqdguja.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tffxctph.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgtyake.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrqtkcc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bieuiiyj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqoshhn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgudwsfb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvwxhjt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chwepyvr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrvwth.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbzlvsa.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okoxvtrv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiohsfsp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxvpxwc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxbuwxp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edjygqfg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnuuawh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2coutdupw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdduspa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrkhckr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tppgxwxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwyaoqu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpxxgxz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnmtrzk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yewhmpoc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wjshrdhb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzbnsee.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyypsvig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2knefgweb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwbcbmd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzsrtgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnemxtb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2altolvjn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pyymydcw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whbqnvpl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjrmmho.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzvztyh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmoxxdk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzusviq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhhuxq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnfmco.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2stzizldv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2snwonirh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbnwyis.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwykstfk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymansxpo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwksfxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcojzrtw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwdbehe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crinvfgp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkjjjrv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrxcmqw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uizhqldi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaivxji.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kldvzoqj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2obhwjibp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzcuihs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yunmhmhr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxhdehk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uowyzbxx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaqavqq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgqmjsv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxrqsrk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxepolr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtergjg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhscfpry.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvduxljn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzbipqg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xipboeve.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjmrnqt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkshxcqu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miinpspg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wddylqlj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnclwhps.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rahoodek.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iguvkhei.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcliecei.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eiijgigx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjilpdwe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urxoedzl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecevmcic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiorzcjy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxmnwbh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kirnhwgm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiwassr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrfdud.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpkvxcn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpkphq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyuhiof.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjbybey.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpnfkzt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcaavus.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqnaepy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxdzvvs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbsgpsf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjitisi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pasunbpm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxwzlcx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgnahgh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qurvvmqi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrbmexl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnjpmqj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfbcpcv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpokjprz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpkpwjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsmuzmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqihvgx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyznwxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obawhgjx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rquxmejs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzybvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utjmsvbi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poliycmo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2oxawnana.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjbesmb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwnmdbo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2finmbrhd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vnttngim.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nrposyny.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nicjggxi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xermyrov.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqaeacy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjomrl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwifwfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hveoywnc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqshmdv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaudkxv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmpdzsh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgzdpco.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiwxdfm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojmxtew.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkbfon.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwaoyll.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbofsek.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nthdflsz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqysfmz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfibvtg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlhioyj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnweqvui.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yreotqey.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ougigbga.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wltiaxyy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfutez.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eprxxrpc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iaapsjdh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwogwqjq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2euzmjxdm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfiywva.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rujcsvgv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jxckxfqf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtnxluf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jtczrfup.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qezacdir.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxjqrih.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqpzsup.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2trdzscvq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2byezyyoh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvimjwf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfofybo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoqfmfm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgszjer.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mljisgcq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvjbgar.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvihtuzt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbbuqpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rgknxivw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxddwzu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpjteoq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xaozrggk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wghytwqr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmivwph.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeafvxfq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqmyhtw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjzwmad.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jijowtfg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmjngei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpdedll.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lskrxqvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnbruop.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ubivcvox.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zknihopq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthtyddc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjokrvys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmucpva.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrybquv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyayvrw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2boerqpks.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjsplb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvjdgze.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2afljcivb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhitgnp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2addacbty.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucbpqa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpcfkcw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xebnrhxt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urgtbjpj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaybgpns.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2szdktnth.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyaubmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ousuaipi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkjyagc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwshyzbl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfwqxn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2guosbkxy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2scsluknc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpwwxus.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgqmzym.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlidanc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfgkicr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhpuvgn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sowcarav.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmoasal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyobltbb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxrlzbq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfedcpqf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2henerriw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2glmgbhls.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnosseuv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azeukzqx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxitwdcj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfsxbhq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2srbbmrpn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hftkotci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ociijoch.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2aijkcqnp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbnledg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpmldue.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lowkqvkj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2noqxxplm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qadmrooq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbcwlqh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtefnhn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2psgemcqc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqadkkj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscroaw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfgcfti.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2brodpcfi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aamrblbl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtpvkek.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xuggsxbv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ilumimdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewowezq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyiwakg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzaueid.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjzypdc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2innjfgaq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybokunfs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujmkyc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vijupjau.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhiizdc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hcudkckv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeqoukh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpwgodd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjopaqf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbchjzf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaytwcj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjvulwx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgubrqgd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcwaync.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnrybcb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2injatbgq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsmsuun.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxhakgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kcthvrkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfyeyah.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvfszmv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybusog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypienpxq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yavqjyuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuskidii.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjnjuqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcstdndl.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cattdmug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqqqdwl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzztuthm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuhdjjx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxmxjeu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgamymj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunukotx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcmflef.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxejkuo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chtiweug.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrnqkly.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2saohwfgk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrdcxij.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaqcoty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgmdpxg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauvbkqt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2efacekka.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yssnltvf.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyiuoht.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsufwtm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2elurnegm.html


<!-- 参考信息 -->