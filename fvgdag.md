代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqpextp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnykqjbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uemptinx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbgscmn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshnmjxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdanopj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhxoliv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbktjde.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kluinfkh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpihjyt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qabnjbgs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xogwjwbp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yttykpug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvxebmc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2icysaass.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wukpdiep.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjizofep.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mntyhesf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wecrlukq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rveqapxw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vroshkbc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uszyeqzq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mujgjgrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcftybga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2teffuzrw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqapfirm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byssbuxi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cijkrzpr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbawwrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eznyokni.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fngpuwka.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2recvmezy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2idbydjze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izjxopwg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjssoopp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yffvzvwv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaniiqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqhrooi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2itnxtkjh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2opwgzohk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqyinvf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bjapbfld.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mntovqfh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxegznz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbbfbkw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwfumx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdvhok.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwiltxi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdxkcvc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhvfutl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slplqnex.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dleskeyb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbedfzm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxcsepx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atqbexpc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvtimts.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlucgyju.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uctxtsrx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sztrweyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzotctcp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmefkfdz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnovlkeh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdnljrf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztthgxli.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzgyvzt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ukirniyy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjhvury.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtlelmw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwsxpqw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwewfuc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmdhcdv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbkzcro.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygddsuvf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uexnjjdy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlwkeog.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2njtythgf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mighwela.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spqqdvcv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scnczdsx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukymjkk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyldzfv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blxnwkdq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaqftuv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgshlfr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2okczgmgs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqnqir.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suohggls.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbxxmxe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkariuas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqmwgdb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sstdunzk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrwzmli.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxyfizs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oongpcqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmbzbae.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhnxyvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngurikka.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noacrzrq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pymijzrd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwfzdnk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwryphli.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ywghdssz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrszgpm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nomlihiw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmqyewc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2scbarndi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfmhrbq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2srszthlt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xodccwes.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcczjur.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxfcrwq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfgagxz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qodvdykv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgorvdx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2falxewjt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kugfjkym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qaocwrrm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lggxvxmz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuomelga.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pytsxpxx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzzlobo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjbeord.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gjagsort.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbnmcvg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skrfrbmd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwxbfjz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlbeaam.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelcedoq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2odggjcuq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogatsxtz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2quqypxyr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfmtcph.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2latfwumt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jguvwsqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjdsidh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2igfoosmz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fadbuwjj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2piebhnii.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2adlldvej.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiltbiw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhmpnom.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnfswjj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tguvynzm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2taigyppd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2narlfcax.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ladbqvhu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omigrkod.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhievhhe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebjhvzs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzpgaie.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdkhyli.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgvsyiu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmvdusp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrjxyqc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqghpryp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlttbreb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcdyoqa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gskcsnos.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wjugydlz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2beyrurhr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoiahvl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoptezn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuvdahx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqyuvqz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pberbrzf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2flygruhz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkiszsm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjyqntb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdegpmlt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvobird.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2djkofubb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nbljrdhd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vteesdje.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmehnbb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rglcaabx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prrugnfu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jklwfoau.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoabggwl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmnecne.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2plsjpjqj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwgivhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2semofjte.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2itehvwza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2clrwyefv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwpzzg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqyukzo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdpkzbo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfitlxd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwayirm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2silxwrms.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqpeisn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icespvkz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqsdjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svghyjul.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmhmdiu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tounwcnb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tibswbin.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkowbmc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuhlckl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snyjcggb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvvwspz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2adethhpj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsilgcis.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqhhqxt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyraxd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjaczto.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bygtoulh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhwugyw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkalodys.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfilnhw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qagszdat.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miltqxsa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjvhiiz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzhvuwk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzwsruu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhscpzgl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpsamqy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnldlitt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2elmsfiyf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdxshlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wehdyske.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjxfxpa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zvckghib.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxynyze.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tadotngl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fffmcude.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cssuybve.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxdxike.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkzoucy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqofwar.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqrwjvn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxezit.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asagzsqr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugakayga.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiikxjxw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbatqki.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkwbkwc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2efpuivya.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lloombil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zobrdldj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwbaygc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzcbkxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbirqzl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2swfdtjti.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2imrhckkk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2alrgnsvp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2amjarouc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuudimj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uixnswfz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwhrhcu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrflngxy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjzxsyh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2memdtusw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lldnobnh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtsregs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zfblczlb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmerydy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkcckpd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhdluae.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2igdfmjwe.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2njvpirhq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlvfsuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yskexemx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jivehvew.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2swelwkvv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbqsvmh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ziivgqgm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzrbfml.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeuekmb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sooywwib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmrnze.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obovntpo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjyryyw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsfoajt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wwifulds.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zerzhaje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2esliidyp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qisxngqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhxnmir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2roklmnyu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2oveyduho.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2bllwlbld.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcefnxma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwauyomw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbsmfgi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjiovrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwrlbkk.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgpzddp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpejxsbq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcieguvc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2foogswoc.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihfcgyf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxulosxo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjgqcjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjmtep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2slhumgxu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cbquargp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhmtwzl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjvzhxc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkfhst.html


<!-- 参考信息 -->