代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tietssec.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjwwtcc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbmqyua.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2quvdlfat.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npamhpjt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xumnhcts.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvfzrlj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqcyme.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwbuhop.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asjutxfa.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhswbku.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkaqudt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsuorcp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2foncbkgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2easjhosj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxsjpqg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmyjmxl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdfkniw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyamexg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2flxobrgz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvwgzha.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxulotmy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqjdoqy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmuzkpa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjwcqes.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2smuxskfx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2etxsbxbd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvucty.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2buwgbdna.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obiitcso.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqbdrws.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wviugcmv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmyraqx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrervzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2grcgurlc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eczxgvdx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfneeerk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaoncon.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znplncta.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvifkkiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmagbak.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trgxical.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2berawwjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gajupsmr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxraezs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiicqej.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uybjoucg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzcshyg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfkzaja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiiqsqv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwarrxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkngjsh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wdizgwfm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyigtcyf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jibyobwg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiovtnq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlltfqzd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuulwcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plhoelcm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pjatuzed.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ltadrowv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkeajpb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2higliitd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pjojoxhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgsjhvo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrlxlnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgeqid.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nfddobyf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydevgq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aowoxugr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyuadgr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabisrek.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pusvzdmn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuacpti.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkkoesm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmthkfz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjnjjcs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmxbucl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srvdnyuq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcukwiq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfyennc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfujdcco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkqozdc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvipkei.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwinpcg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbjfnzu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtctywcl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbwcnep.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjqvxfa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsuhvoe.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfvzftc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2smhheyee.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjljbcm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2khmtixww.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyyrkqa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzznyia.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcugwou.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auandmtr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlwttom.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bozjhnte.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rktjnlcp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sttvqvmj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wievpjrr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vaslojvm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2boovulra.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geaycccq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dklcwabb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkofgukc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcthhdn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkizoxq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfteuak.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkhuanu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbevzbl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2awuujpce.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocowfrto.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwqtiai.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guyzxqgd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krukwrby.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhegjao.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxjlwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqhnacu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2weoszeiz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eljcfxks.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2opdbuvqt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzorvbls.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wclfwbui.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2plslkoyp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2npgmufhh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yezxrdoa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsyayak.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qtamwogn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2aasfmbrc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nafqduni.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrescsto.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfivyxa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaaafie.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhsglas.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrnwcwb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2najlhhdm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hedceehd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dilyfrxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlkevcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgvtqav.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqqhjuv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfvgbej.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrmsnpt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqglfonx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peflihrm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uszdkoyf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvmmadh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cstyujru.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iugmgzet.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzbfcnn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqzhsrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxlpfyy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2poknwzcv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbtankx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdgqpkd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2thpojxzn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bifmrjlt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbunhsdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrwhfix.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvonlye.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbzcohf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2htfiqkti.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzcovcb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwcpszr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eridyiqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjeqkam.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxbhjqp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrugnfr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odorqlar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zteeflry.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuwdmjf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrmgqba.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvhuib.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2clkojkog.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyozhbl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2innvggbj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnctrbh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2elrtylns.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wjabhkih.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsitfpun.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcfdedu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pbggpdrm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nufewrhn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzsecgw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zexiqtvm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2trpusrxw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eznyfdpe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyqupuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rfigzugc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2miugkeys.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwkvmsd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvncjud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iankjqqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqrtofn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowxteok.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2twzktige.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tadrizox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcbppjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihukagi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhabrop.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2crhmkqko.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2erfzfern.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wligpwem.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzmrwf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfffrpe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qxddmvum.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mqttwtng.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lxncawaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwjqjpc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijfeub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvugfnag.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfdqafj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjueszpd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkpeuyh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpuddwv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaapkrjy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqtbjnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxwjjqs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vewmblyr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yftzttbh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qpasbllc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkzkupa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymipmbzg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrpzecu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arlitbet.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkekphuk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoprwog.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rymoysiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlgnjib.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcmmcfu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpudbju.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhfbmxf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhmytwy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjknzfxu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbeeixs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoiqiki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjseavq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2klduuyhw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llfbplus.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfslmpb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvwnqua.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbmvlfe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnuejdn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pttvkbqq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2garefbip.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvevfae.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcowqun.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgsylyw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvhnjay.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrkxww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsczzbh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mchbwazz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjseszfk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdyxhql.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fshqcqhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkizosf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoifceo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2arshggyh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjklnkxt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kjscbgjh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtrdzpl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqsyyfp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfdxso.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmdgype.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lelvizrv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dycxmcou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dosdtfgt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkhybli.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ednnxekp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exzjeohc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhpvjd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgbljdr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btceaita.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2legiwlqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2asifjdsp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2amwyypsh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdyoxzs.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2smagwkme.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxsejno.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzkuojv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2chgsdsfy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfzbhkt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2inyxzqjw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cioilbqm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2psubegpq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zellyrko.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dweunnss.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjputsvo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odcfxupt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsctekk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2csaonovr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvclhbrb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuvdyzr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqidyavp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnsbwwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgywgye.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nixlrpge.html


<!-- 参考信息 -->