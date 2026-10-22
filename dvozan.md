代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgidcac.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoogxmgv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dstyafkl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfskyrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sncbkuky.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjjfkp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zktnqoka.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvdhxz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2soqltmrh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdobqabp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2srisoxre.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwqlbwy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zquvaizk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ampajhoo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2drcybafq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsmxthd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgmvmze.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrhvwvz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kefcktie.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhhikfj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqgdjhr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jldwdyzc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2foczlold.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2urnurekz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qseiheta.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhakhkdj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqwqkbt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwljbwo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bklkktrv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oprmypax.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axhxdbcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxeucbo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2miloomwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qszbdplg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2czximyyp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkwolbt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjkzxmg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2waenqllp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwocdnvz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2slcqinnc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okqziets.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkmzabp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vethifcj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbalweox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djimbsdh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsrskxv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yldhibnx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zipwdzsu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgguphyr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdaqwxm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcenzdfq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxdunyy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gvalslrr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaujxsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnsvmmc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2acxfvtlw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiirjff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2grdjdjqg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxglwjo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsyrart.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cglbxpug.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2soypbsbx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruduplpe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqrjzla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkcgmyl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2obuxtfia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsawybg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzbvsbr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2prmnzgzx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfprzeq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsyhcwj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enmizogg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzpwlzy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxwvyei.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqegomu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrsircz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiszfjry.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvjsbvu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maqgchld.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxzdeow.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oykfsujn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oidwwekw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytperruq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxrmght.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2errbgcvi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpdlstp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2swfdtjxm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpjdspk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuggydf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2brbxfssq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qipeprje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsecmcs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmtshlu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmutyll.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnnzlwn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idcimjsu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plciugnx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmwiknz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbprzwc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bghmknim.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlgpzwd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhupnpv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2coehjwmw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2skrweclv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2okvpbtzp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvenrags.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vukspsct.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upgzwdsa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfdceiw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sjonsbip.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whdigevx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rokirygz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjoiqix.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvznekz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oauprbxn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdeupcn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjxokhl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adocjkgx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhzwvfw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmssfkr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhcvnqw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnsgddl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jemvqrvu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqunzxxh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyoqtzw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwsifxs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2laonittz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaxmxyq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxsjnqp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nawcvehw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2auqmvrqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rvncqjjx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjpxkyz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnxkbge.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgnmrpy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnggomsj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvstnk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aabsuaar.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jylxyfdq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmkhwz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtacjyl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efxcjnrz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqacep.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdczsuy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyjygfz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdiaevh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aweiarmd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylsmmwl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlicegqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsttnjk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtwruyi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivteovjy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkdhmic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2avfylgmt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxqogfo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pattmhdl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2llpxalij.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyorpyr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aitydqbu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsyljfg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usoqrmmm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slvymlii.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwoyzyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcxiuzb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbwrif.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utsiiyyn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbtyjcj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnmclup.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdlczxk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yppherrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bchdqwqh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evbjiytz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cynqimws.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxraunb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azpikwkk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmaflvj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzotrgm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uffvmmgq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpayqsr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gosrmqrn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgrcfgn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgzwhvc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigdfobd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszykfz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmpxngr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyqyjoe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjlytdf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqtrjst.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvhibrw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpchannj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2exgbgbvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvzbgyy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxycigj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wyblmweh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bdahopos.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrbiyfd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tphweosa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llmaggzx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdinyjhd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xilzgqvx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gsccrqop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxtqnx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkpjkbx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotkzdl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxwspms.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyttaglf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohapiipi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrwbpsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bavgfypy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuojsqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nxueimbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swymwmlg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdamkyiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpnzypp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2crxidmnd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsycaud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxqhkew.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjupuwzu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgzgnqd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igvgrkqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzeexkl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2badbhhkz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eanskbkn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2phgudfja.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2sivchlrk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmjfuvs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hokyunrp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaxwrjj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igrkdlke.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ruttfczq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkurnjvk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwljoftw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgqqlfg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2figfgmui.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jblsgtuw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvksccsd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxfxgmn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcikuyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvqidsy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwhxwj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmthhzua.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiqxror.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pkynkogy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wedgagbt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqgvigy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqupckk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwirirc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazwcqxz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbnhfar.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaajlik.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvklqrob.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2txwpzkqb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwgujfb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wewhbzzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxbkrz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhxnzdu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtbhoru.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljjosd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzkfwc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxheal.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzhimzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnscnnq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzquhkm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xuusqvvs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmarridf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwwqaej.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yberlgjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gasznpus.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfvqxwa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlrdjtg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2spjobvhq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2apajcpyi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbfxgcs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvkaudf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2klddmiqu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vskynawe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xucwdeun.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2emqxrbhf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvnije.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qujutsbq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pdquskyl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkkzrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjyvpex.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggstfarf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2codnkbul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2awltioiv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtuhxub.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuayljs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2biuwgpba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2chzbmafu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxopwznx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xklhuchg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcdgjwr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpkrobk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bpapxvml.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gakdbfdj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2byqfurkz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzdqwvq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgpsecn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpqnmyb.html


<!-- 参考信息 -->