代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eacmhlho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuqpcbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcygndq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dudovzrn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2apwlsivs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqytpgc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srisjnrx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeqnpgm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tadqjcms.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zikejtje.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaudafb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvisxwz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bokabrqp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwxdmgd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvjebzh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmlqanp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxyjsmn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpxklcz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvhlttb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzgyuqc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bbywoidj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xryykxto.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfxoyfu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hebpsnmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtyfusj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuuwnng.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2budvprsq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eabwuuev.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgsbsxt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tuupiwea.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxriuuyf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcgllme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfeffyw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2icdncvbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyofawuh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jubgcnrs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyeaevv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdhonjd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usevzook.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbygxej.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgobyzw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmayjiet.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzysjznt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrvlomc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gurhhjpo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bahowkrh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvdwakx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzpgafq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jexmuvqa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xymvtnpv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kphrwnnk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwhdtnl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgobbsvv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wydwalua.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wktfnaxe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slxxwxpg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lobwxuej.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmxuzgm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eupfssbt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzabmi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcejrqte.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnsmcui.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2unagwysd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpdjixl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmilbcz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkccydsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvisdna.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnhrjqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtevkhm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhfihl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smcbuvpq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpmsvdf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2htytzlnt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuierbwk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnidftvn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpkrbph.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szozeypq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ecruraiz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrohtaa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlehcjlq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lphhqzxs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgutdzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkqhlbd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqnfcfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgfwpyz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaztgecf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gokodorr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwmctbi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nozpulae.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otcbmgef.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vildevty.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfwnfjg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmffejci.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiiuyuv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsdzunt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtuberi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2djxqhsvz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phsljzma.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xrurotit.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvuxlxg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aupehnvv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaefscye.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iehzhkpe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iumnqiix.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvawbpjs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtdpimo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcyohmj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgnlcmg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lqulnjmw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuwgxpa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhrqjqj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhuunas.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcocvnq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2galohuvh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeglesb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkxrmqw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeyegon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2whzouptt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsvehun.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfwoejf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcjoipk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2slgiwlgi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfohyyq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yqszvvca.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrzgisf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnpnyzu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rpacvkai.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wranvyfl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egvzfzpc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtuwcog.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpufoi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcdoyyq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cebqmmkq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blvqdhia.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjlmtgl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bldnngwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsazwj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxuioff.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qckeotgy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dposahoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfkptsc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itsqkphh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fguvfkzu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swdwgdny.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueferdit.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2papdryus.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkptdzv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxppjrmd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdsmuvy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjddpgm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbhevn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2logppjjb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2flmxljsn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hioxkauy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxcccjh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxgxcje.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecddkayx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaskcjg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuzeamw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2icrfujce.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nznizxzw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fghvzujj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwgtwyr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pubvvrkb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yvielyhw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdtobit.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxwhwrw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagvcxvc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsbptsd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uurggzjr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvscfph.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sejgoxmk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmmrnzd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmjabme.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckobnmla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiefyilr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qgompjzp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhcossu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2badcwptj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhezcitm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wivycxkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uajmjvoq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2coliyyiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nayeeouu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqitqey.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhcflfg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxaguxe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqwqti.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2culyhljf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grbqvvjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjevuqt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqwzbcv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jynsenwm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrovzgmk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfolgut.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eruampjv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfixolr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmfhhyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vspfqzjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yufinbxn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hnduxiix.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqtzxgs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqlglog.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgbtuhb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfozewc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2apuechbm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2grquqmzt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuweasz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbhjbuh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrviicug.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ybadmgqw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spbvlybn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plwoegmq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgizyuk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubisqbwy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagamexh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eslehatr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptikatgc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tljdyxzq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpnpjga.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tviydwbc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdavpfdf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpxncjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2turhiqyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfzweor.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqhsnqs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snywmlrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcycogz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kobqjaaf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgreegv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pyskszap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fsutfend.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkytxskm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvbippq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrtniik.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hikvqzgc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxupbhi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nllpupsv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wguvjbdy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2crjsejla.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttswcykk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfcmcws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhgsmpk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxbikwx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2umfnnbre.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtfeyai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2eohgwdqk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2udacuhbc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsjacpc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdwktel.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvyyquy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyjyeop.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgpiccx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lsngvklt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oocodjdr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2prspnixn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnghwbo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjdwjae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhhpqxq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjqsrv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyymgwt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjcispf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsxfwho.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvueqqw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmfflso.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhahgnk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjmlqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qvznmzhn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpkwkvk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeekdxr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2usruafde.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xodywokb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgouvdit.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhygalyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chrkuwng.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnljnru.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryagfpgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpkkcbl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mejntzja.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzrjstu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2quelaqel.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxwfatn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnfudzm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2riqavqhg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2raiaqzjy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyxavoo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcomesh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyehphk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2evlnbnnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frimckja.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwolbgk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2upanjesq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyppqjm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ocedxmac.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkyfgvr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkahppa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iboarhui.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeprudo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2puhncrzr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2aulunuxm.html


<!-- 参考信息 -->