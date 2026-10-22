代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxeksnp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsyhemv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpozqxw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nompaxpp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmokyvy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2illjveup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnigfrx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiucsgz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhoblqi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrteghna.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wujkamoi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkmdofr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclqvsrk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jojwiajt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgpczks.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzggtxv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2aieioaft.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfdwcmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpijayox.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqlqpol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacooco.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgkvqru.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsymdafq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2opfxajvn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2amadjhbz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyhfvxr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirktmt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dncdbuoa.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dewcgqoq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snudgdio.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmytjynf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bckbjjsn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfeqiyw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyhxhuq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vepoxuut.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfsphwd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmyubmv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2efrtivcy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgnxznr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbsvxbc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycthrupx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgffwgfn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2daabinrd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwgrvvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obkfbeqn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axftzkfb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xybjfbpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcyfqdn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2szghpdpn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrgymxg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbvwlil.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagiowgv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcyjrxx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrkxvyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnmuwru.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlzyzgh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmacdefz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwqhdnj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrnbnhy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cifhilup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qcthijjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qbanfycr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qammzfac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ffywtdtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzkrmjg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfhwluq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdsltfa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zivdugdu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuyozku.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqaztnf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykozetxm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdoeqkv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwuhrom.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvqqjcy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxbzrot.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkvdao.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycrkqk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2snhnnjko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmtxvwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xacinuwk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrigvty.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhstizv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yikutcrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnzqfbw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lppgqahv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjkekox.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjezkihe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxijbbt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zalanxec.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eweiyjqz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzbdffw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqpxhvc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bspwjvyd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eczpiuhn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwzrzfa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjbdcfq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsxmxsl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpawxzi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhqzjcv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avujebqi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpioxah.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwoaun.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsemuaih.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sudkosgp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dnubzrqg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zygeprui.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmgiizf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbnbxj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgevlxzj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxcctoj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyoxdet.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2covchlbv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhnjqqm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyreghtl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kljebzkb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeicftqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaiaspr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxdwjeb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtivmjx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmbtvet.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpbtisw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfnlfrh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvbqtlh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmmtqqu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkzhbyn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrfdbr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbttvdu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvtokgr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiwkfpw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnyoqye.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpvraxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mazxroyw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyfpwne.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otqqrgbc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnchyumv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvgrckx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwaygnu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awzlxdmz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slkhtryq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwrulpi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjbfiac.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfykxuzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2aquxrjyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvderues.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztvwxmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szatgupn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfkxwbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuehxor.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mmamghuo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmchtgo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzvkhht.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiqrvws.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoylrvd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bykwchhs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvohico.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdwzsfx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xmugmlju.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnnlezt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzuyrdk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmxvqqa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oarptxkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leakmmjv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfkuhpc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhmhhzt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntitgito.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxqolsu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqoeial.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzenqc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiiaxud.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tceovrvn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azyvkeek.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbluhkde.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipahurjt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrthaudq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppctehee.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crdvwymb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeeyree.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kgephnjb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2szkhptnj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tenwhcdq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2goeybmnf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqtampc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmsmmqb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvjvyas.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oaepppkr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjfvijm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zppxxcsi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzftvvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjudsjn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brjjynty.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2avmkteha.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2byeyzidx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdohbnn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrmpawo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pluieopo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmxlaql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbpzbyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2crethxbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhvbbrl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsdcwgb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gaezhcqh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2frjjmzvm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjulso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwxypqt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yishjuib.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2spmgcuft.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimmcwqo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsbuymr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhyhifp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2virveuld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yurcwmfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeklfaf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqaqhvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvabzfxe.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtqcrdd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfqqrye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxacthi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dclxvuxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akuhrcaa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvpfnnk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmizutt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eixphyhj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2babnikix.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdxcnxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqonify.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oemqmayy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyyanoy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvekjze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqbynrm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpyehqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxygervi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpgyjgy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vglvallo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqezsite.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgzmetk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2opnfzyzz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pksverod.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2szilsyud.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuziazb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2npdsucsm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2thrjwbuv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asyudrrs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qvczuykp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxhsjkq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxnjfb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qefgdcoz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmcrhkn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcngyan.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qolwwmyz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhceqeyu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaccppc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnzrwwn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rodliezt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdebzfd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnttrey.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtenben.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnknksk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xusqjqpv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ermjskkc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmeggll.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnvvcgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2roqwpbis.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrnnoxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fujccmyu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxadtmqs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjwkfcx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2deliwlrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuihnet.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2veyiyxfs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdjnofa.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkscyzih.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsgbjwy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gteydvlg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdgftur.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pinkhxef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wuonzske.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tznwdlyt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvptip.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvfxeac.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2igduwjik.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jgahpkbm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwfxhmq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvcjfde.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcvuqkv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2woszpfnv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2awznufoz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmhtyut.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbkhnax.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwnyhpa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqhheqm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqmvhkr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnewxwv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aqobpxtl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeeprpd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qanypzif.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgovtcu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2jomzfwvu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfvofa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oisanlpl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zghvlofh.html


<!-- 参考信息 -->