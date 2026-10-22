代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvmgoyu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upgkjtla.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dagseqjg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2waixawpe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcfpcrt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpnrsec.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyptnofx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2httnsudm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rdifztqh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jaljruwo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdjselx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdfmhby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhzewu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvftodi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ileizmap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyipch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxyiqmu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupakxmt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbrwfsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kizlbzua.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klkzrrbs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reaqkvhz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjrmszh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2joisqicu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scxlgzjh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hncpdxdk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eibljmql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxpavjb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2suhfbneb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrvhbbr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftcfql.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yyraysja.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytdavbq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaazgmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2skszahhm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbefbfv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdiorzv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2glsecgpw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhedhaw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhruicfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oesccdll.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlgdwex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bznihpph.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqofmtre.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdauprs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slmgckop.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asvbiwza.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jljiyfot.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfljtyx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcnlpzj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdppiofr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvthbtv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teczcqvi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fkopjtfh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlstwlev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzwmagt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvfellx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gukqvxfz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjehqsxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yijdxwru.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqphkyd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuniypy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpjrvni.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwctwxdv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dufaiqhr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbjdugc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgczoalr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsviupm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrutokjg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hllrtfdh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbieybok.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2umqpuyyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnjxvce.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdarlvuz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgihdpz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwossqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrpzpak.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwtgpqy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikthufc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaagugf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2egzigakd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gadepznk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiryzjag.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tipztvlt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxyist.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2siiqgwiz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrepaldt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwfmcli.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyuknei.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2chixfyuq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkvbvwx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzubfyf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpogbko.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvymtyzn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzhgne.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbbidrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2behhdrmm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dicgewwz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdlothu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gukfzeqo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2moqpghbl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbzuaun.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaofljf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuuufth.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2svrqhstj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaidgat.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbkemno.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfkjdsj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yohtzyhn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achorkie.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkofto.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqocdvmw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vchflqvz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fryenddn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqblqcvb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2txuuozoo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2alfpfpcn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mimcmwla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tngfitqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txpkigmy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbycorrc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gniwzjqr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuxkkof.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrxugqg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yiinqcmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzrqecz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pfltbyxp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvoapbp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dldcdxhh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cpixmxld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2twyqmmwk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtnhabm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2garpxfis.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nulotvyf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqzbbiy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paevdxev.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwiuwee.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeltcxi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqjoaxo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2asbqcqds.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrzlhje.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhkpflz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrwvqth.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zezbggdp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pymjquhv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mscjvasw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxmruzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobzehhf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqrmrit.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nddrmpjr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2izclojmr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kagvbymh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmkmpe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zsamzsec.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaaitoz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yutciwfn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2svaeblop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vpepafrd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdwcrgj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nwacnqre.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bjywgycq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxksirhy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2knwuvqku.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwuexq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2udqzazef.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmriqtv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyieyrjj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqiabgi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbvqrup.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxveaz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hxezclkd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkznycb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yujjfrfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krjdtiud.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwxwcev.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrzakbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjiqdd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugansduj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoufayd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnxzhkz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2otxlcqwi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2alztifmq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqxzyel.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbrkfr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ssklwgyk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhipkm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tkybdsrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfanyrkf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmopgto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchwies.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ekybsiuy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagioihh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfusxib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcgrbpj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llcydjvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagjzbhj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtlxsaj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyivobb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrtzbom.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyijzwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bstuexcf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjofayp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyxxmsx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqysmuy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axwiwktx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbipedlf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjwxzbf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdogpjih.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2weydgdct.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2adzmlirv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvoecnh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvaqeea.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2flxrvlik.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaimckc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqkstqe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2natqssuk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqutjyf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltatbdvk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2izpwtuzk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iazeqier.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgerntr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgcupfg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwazjq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtoyrnc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgpnfz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlbunbk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grofcxty.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbphngc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzwialy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxwkcrq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umnsgqth.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znkljheq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcwxrqd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsqvgbw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuzyxly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2snkukmgx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzgfcjn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuadusw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2skkjbwrs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqfvxnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtkchsq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiiblpd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hslrpnow.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lfouemoy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dishlomp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfluxpj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfhlvl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfztxylu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvfstlx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yayuqfwb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzxuzpr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cmubhfzf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyvgvbk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuaxczk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfcrwsl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmgdwii.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbzoten.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxdwhdt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdcsnre.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxhefxq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzaxpbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvktueo.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iwycxziy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2poyxynyw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbsxfex.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiyqpda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzjhtsi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfqygq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgkwcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kciarvsf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkubdqo.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdhmctf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvjcesw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqirewa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyrmqkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfjudmg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlzljaa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxyzaog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbqzyqy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpxhecr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcscdu.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kprzdqrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gappsyac.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnayazb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjbkap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcihjbo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzbxawo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxinfep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qezverzy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyllxeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pobzdaks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2syuowmjd.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvwupxm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thfigbgu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lalzqnco.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcgnraz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsttfig.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbqqkys.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrpyyc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnyfwwa.html


<!-- 参考信息 -->