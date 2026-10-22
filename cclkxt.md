代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaobqfd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifizwytp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cggtbsdz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snywlpaw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uifljxhz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqilyw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmvdnlt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvdpzfr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ambojpre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rspphlaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2beujsaqf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pniobjqp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdlsfve.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuckizrm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2etixmuey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxcirll.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqnaxsx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsktlla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqhubpd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2waaolirc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvthclug.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmzfeka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzbcarr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvvrfxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqgisga.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jutavsqh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkmddkb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2esgawqhs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiaqjqa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2holuecot.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnsvznb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlzmte.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkwjmll.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vokuemeo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2httdbbut.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwnfukz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkdklyn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjxsen.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2miywfduv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpewdsjx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiqoiwp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhmhqup.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grrwapjf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmchawaz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrcrvvx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtxhtfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtdygec.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfwejik.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnuxjqq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtnzakj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbfpffo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brqimzru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndujwtmp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lffaonqi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szpkwvvz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemnmvoc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvggphs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyrrgse.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2caelnteo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yyesbaix.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtetrl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjygtba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xccprkwb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2thtkktrd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jzimdvzy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tymajbkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebgsxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2szwzwwkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fufdtpgm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2upyviegr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjstpfvd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkusmfux.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjonzes.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxxkdh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odpztytp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuqkmfc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvyqywv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2djfqdpjf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfqliku.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvgeokp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vveletve.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ecusvcbs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eydogpfi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oviiocso.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seyyxwaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eylcnvug.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2izukpdvk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzlarug.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoyibio.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjdffqr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyugkeeo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyerovx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuvgrwi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqwcskd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jurvdesb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihamwjlg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfaewee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwtmvby.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqnjzgc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2weqbnpmi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticzspkg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2folwmadl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuxawwp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ambsocvj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aluahdms.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umnnomia.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ankfkxsi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qczpxnbp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdvmrqe.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwkuhvg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxcjbaa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhwfuee.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miywfbli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdylecg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsllzfpe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlioeqoh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaxzwlz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2njohbiyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebmsshj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlysegx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmieeudf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aextnbcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxolopj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awzchpum.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsaqirf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nkncqlgh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnptoxhf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxayzhx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zutcpnle.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2njarmlyi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsqsrgn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzexyvwf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jldcsbkb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmdoll.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iusonnhx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yixzorri.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyafnno.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yysejcuu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfadztj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iweiyclp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qayxdjft.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeakbcd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tllajjwe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrlbhio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqkyrcs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlozqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fjarcnfr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoqvwbk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsrigkc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnegvdwq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inbrevud.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmkgsfm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlebuqlp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfrghms.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2neokasra.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2covbluml.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xyalszhn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwxqnzn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kcajgogt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbqvazi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuprxpb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjhhimg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzygnxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmamrwo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rublpxzp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkgilex.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pixayype.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlfrlpy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgobxte.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolaasdu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaezput.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2znyygrpn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdubppn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liyojsni.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbiszsv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igapaqgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekdzria.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoojcbh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eewtmkmj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgtfred.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxskgij.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bxduhnnk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gkypeebg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2egipgkra.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcewea.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdffupw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqesua.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aarogaap.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2txtrefpa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjwzguc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vupnrgna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwdsvgj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hllijdlt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2porrvqqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcccroo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2eykoulry.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmrmjch.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gaivjfxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbbpxfo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcvnalq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2shryqaci.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycktmvkf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsofnblk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2izztiixf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dukrrnys.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaxrhbj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzezonm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qspllrxm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2eapyewrp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkkmjvw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvizqkn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziilykvf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdhzwwf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dgarailm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpnygmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tomlgbxb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pemrhpdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzugoyi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdaxqcc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyftnsu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiejyjsv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dibblyps.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utqovatt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbblkxrq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpfrwpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsclbih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anyliick.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdzosqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiprcym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csvlzsrz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyldumou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krtfetqe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvmvkuf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2svbwrlat.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaxfxkk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlgngxv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txbtztre.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnqrtf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgposqcv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrbjrha.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cydvescf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fugrguna.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2oercqalg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2etqkxlsz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvspqvdc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqermiwv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gmufppit.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riqmlaxz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viljmocq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2balwqacq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xolgpbtm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmuhbny.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsunstl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2disgcsub.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjrrptv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgjhwbb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azzlushz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpfaqwc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoctasl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cquorxpr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zukqstws.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mgusfopl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oljjatvx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2exqppikh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2memrfdyi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwrgtp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdclwnk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsrmwyq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiampam.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2abknwhlt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2achrheuo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2glkfzdxy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdihobb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzufygd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvbhlf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzjllug.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkenhdz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2syejcfax.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzxynoe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fywebbdn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zijfkffa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iduhdvln.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tymydrjk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwjaend.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjvbwjh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfeabgs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqwlzcf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkkhlqd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzeaspn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jstmfthh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpikzfas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrywkyj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uruiloms.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfphsxhe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2navptsgx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejmifhe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2swckohbb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzagvjrz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuqmiqs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpdmjew.html


<!-- 参考信息 -->