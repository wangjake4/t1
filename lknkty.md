代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzppgbuo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvrrih.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sszoders.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqutyzxw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehjsgdl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhirmoc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzrkmqr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eehdxcac.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxzkpjq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utccxglz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pactsfej.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oceytblt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsmidfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhczcymx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2djmibzxv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqjgquy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vddefjvj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kueflmmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utbyibyn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzxkwvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxebgubb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgdpaps.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jthdarnw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqgiogn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjdmcba.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqztnsv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lndtzqve.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmytby.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlnrxhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grsfqyfq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uczeuthm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfqwqi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jcechbiy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xswztywn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhpkwl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcibsrkr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gveujogk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qoprptlp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdbrewa.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhscul.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzhvadl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkilmjd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2utfkdalz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkhttoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooayoake.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhxtkbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odnewdnl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxciqlp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pxejvjxd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkgzvdq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbpkffo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvoosuf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxoigxi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eioflkvt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuygswj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwwkcmq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oizrcmcw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxhceia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qebmfrti.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsoxbt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmefmjjt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psennbid.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fecpoben.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyztkkmc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doxcuzun.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyuxeze.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vowtomxo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uchrxrac.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxduele.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2acumsmee.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohyzzb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2onmmttgd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqmnlpg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhxpmrt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bogewchy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tseobmpa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igxjofuc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfwvsbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxbdjpv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnixfaq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqyhqpa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cytoioul.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlljein.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqqzqjo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2arppgcyt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzrjaqv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imopedfg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdrjada.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxxizeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2crhdudoo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvyrxut.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xodyhwta.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxkfwil.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvhqloz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gliqdugv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwrnlgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqvxgaa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwofxqq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhuvcxs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwequmbt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqnoonu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odcdaiai.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2leibxioy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrltaxy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchsfvk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqxvkg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cirfumrz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kstadghd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtwkubz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzipzgyt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuoalpy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvzkpr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slsqmrry.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udqrvczy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaflrqjt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyblhfdv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cufyvxjl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2waqoagto.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueviahdg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfslbkve.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpmbdsr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkwieu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2upqtemad.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtilssqp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rafrpkdw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2unyheapu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnjqvkh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwfwov.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ommnltph.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2otsdyuhn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lensbazu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2isqoslgs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2srnqtqyp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gomtvsgk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjbogm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrbvzys.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2voqomlmw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pceogiva.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbpepjh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjjziii.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnssyvdg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjftwxgi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbwniar.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbdtebj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbtmzxa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rogttnpr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2keuypqbb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kspfxhhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwksrab.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkzocig.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joefxlnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqhvzh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhiteou.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2epxaqkku.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pltgrrlv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfgrfkz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexapwo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2etjquvir.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfrgdys.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ktazikaj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2txgbjapj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeticpj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpvacrq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ecclazmq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qakafvon.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqehpsy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlgyqve.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnklmoo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sctqglik.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgszsvd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavqmrfk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2keebxisr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaxwuge.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2huidkhdg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2masdlpeo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvayblf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zndncowy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mylzuvbi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysglgrms.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcxhhjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwaddpz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuclkxo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpzhafj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvpcywr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcglvhq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2itimkxwl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdepxiv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cayjbmiy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrivxrr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtlwzmn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdsdnrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzxlinv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjfgxjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxwwclk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohtyvp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2estmphlo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjteejwh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxrsoqp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmljhicp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clkodlwv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcwqqww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmudgfrb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2picsgfeu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmkabxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2coujnuma.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidjdian.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxbcmoq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbykutq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcefnwu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamtsbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmwitsc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgaohlh.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wjofgxcb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpiooua.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzaccin.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdagtdik.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoteviks.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gthjrwkp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtilqv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnxcfpq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoywsmz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igzendln.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzsnyd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnwvmbr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfzaqk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igsroldj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvonffl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbgcbwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzstkafd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqlvpbw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcnkgvb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ninninhf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twcscdsm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuojtbg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qudalrgd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjhsdbm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtilgin.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gduxojxp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxfloxp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfxdhbh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjznvxa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkuwdtl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqapmyw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrvmhux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkivrgro.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gffsxfsp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmedaknj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgwvikp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2imnjetie.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2iczrlael.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2icitrqdi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slxjduha.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vestarnf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzksmdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvqjvou.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ltukfjic.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nziueddt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxkklti.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2arsdzpvw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2znbcjesy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bocaxngi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mirtouov.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmlwuuz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgqzvgh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkdltsx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyxclcd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nahhcvci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2norgansf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbsophk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tecgekkv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmuvbrd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkwapec.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvxrajg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcimyzhd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsrsgrv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wknpbill.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhulvnci.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmsppol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2izlmbixz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kqomeaxo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2cclmfunk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdyixy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2otamdkwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsrskmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvxfwyx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiyqona.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjydsarp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnaqaok.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcmsxti.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsztnfh.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsmgkxd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxhrwn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2okyuaydt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsvqnuh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsczkhwo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmprrpqr.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxsdxia.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurmdodh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxacuuy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlypjbb.html


<!-- 参考信息 -->