代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epnmnmeu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2evfvxifc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpumufh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scrapzwr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwubxns.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfghuiru.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcntttn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpgrroe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfshvbmj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzhpskm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxggtehj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2butznkea.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbfbygv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrynzld.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmushmkr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2syaqeuwr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkqbogc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2odiebiec.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxgwajz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyuuqpp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrgkidx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoferwmd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmmwasc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmoaruy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhovcv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxqwot.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvedsdlg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zayptdsz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2egqbtvep.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wurczbqb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2onofbvef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzigkzbt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbdkwum.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjvdbde.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2misrmsvt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiouxmj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbibsts.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiepkva.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2thmfshpi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njvebluw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ggieqgsm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rggkyyuc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkkxhw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsalsqls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcmbgrl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2robbpbrl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgjbxpo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zftxmoiv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoagajwu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxntisx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pahjynnp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sykgilti.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2digyenwa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxkgtmj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvepulr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaknntvk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmusqek.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dttcjhof.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2erayfppq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gkquiknu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrcfnxd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wejlgkyk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxgfncq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oksqgvqc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqlulab.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcvjhzl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrcrwrw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mnycuoox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpimskx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yojaaqla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfbbmbn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2towwirpv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgoqixw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkxpwpk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmppcams.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzycdkni.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbbvclu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2frpveqhb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hayfqcgj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqwrtip.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjxqcru.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2togynksc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2devdkskd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgbglkc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abqjmpmh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjutwny.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjcjfit.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfxaklg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evlungli.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ustezvud.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjptebew.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwetiaj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2muinzojd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2himuekdf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bofjwjxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2unpzrbhu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wehiprbz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvpfuez.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qumqhlhr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsugrip.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdtycky.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcbajbb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krppkinr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrosec.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nisymkns.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2welelwxq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuieqhp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ukallvgc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnjxuaf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnugojay.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezszkpjf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xinxxvmf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhpsprl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uohpwgvi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuinusd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzzkjzq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvtmzns.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqbmedq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhdajtc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhbbljv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egugcfuj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqzqnry.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eibyywuc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otqospbe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2imntrqnq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ervpvshm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2odbfeekg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvdmwre.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtwwriu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeoeizy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pojkzbky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vduqwcip.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbfovft.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ureulrgb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nuffddno.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2undrmzqn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haqjiamp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnpuqyj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sofethzb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mljhuvkc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiyqequ.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jurhyvel.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdobtty.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wgenvyut.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxvlgvt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mptsayju.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxkkvbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amogjrqo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdegsxkk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sanjlzwx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhmwjsz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoajhhx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjprwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkbijqn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2udfnzosk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpgysob.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2alzolski.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2emfievts.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjoirkx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nifdgakj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mzikyvqh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qekxnoyr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qqonnerv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbyknhk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozlyaag.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aljeuyhg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjytdwjb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfpkpgu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsutkixd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pllfmobj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfrakof.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2saqsxczb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeadkuox.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvekrvr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrhtydh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmgmuqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjerkbnd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nngpqalh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvthodu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpzhpih.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfudkaa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvljib.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbrpqbn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuouevu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszjqpv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqeiiqw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtbmszf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkttkqtn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ekomqqig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2okpptocl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kixhclnj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2taoafaiz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfruupg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpkhryp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnunwgfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iheddrpn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvfvqzp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqmajv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxrrqh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmrryub.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzbwczk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgukkwyh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugluexj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkydawmn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2shsjdsah.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvlpxu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnzqaha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlevwkj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfyquge.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdvcopt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgdsmwy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2udxbmehj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoczega.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vjidrlsv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dxleboml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vntxwxqo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2synsfyvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eamlkvvx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2exabesyp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgqpnod.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrdytjb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxecger.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krfnlbtu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbnwudw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mmukthrz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaforfj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsausfb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kpblgoji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyobbalp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgelmvbc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntzjibk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfcrqwd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqpuueu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gujnggrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hifoqszy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gimbqzjf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrwhrwh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yidthqfo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjhgrku.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjpedhr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bghizvbt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2psutulur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvwjlpy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwccduw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsjijrc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huvaekta.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzmsvd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxfwqzn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvcjggo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2migbyykb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbssomdx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrsliss.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2okbfcfcl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpyzjlm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjgflsn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nowotqid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eculuzql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iapversq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dveaczqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuebjtsu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaloxav.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckwavx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmievm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vllvruqu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tegrzrqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhcvtfq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqrjflf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kksycfxd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rltgisni.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuvawzr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rususifx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jaetjmga.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qabhxlvw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2htwkjjms.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxokxzqb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexltczf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddytncka.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzldjwr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxbyrft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdonrj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqryodmi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dasbkjpd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uebfkfdj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjzbmnz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rplcfgdq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqbxoat.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2anvfqyoa.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrocujl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sfchpqwl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwcwjoq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjrwtiy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mjethbpt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vprsyjnp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ympfjyan.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2auqpwpvi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatnnruv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tncdpqwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfibynmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jsduqalc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyeympc.html


<!-- 参考信息 -->