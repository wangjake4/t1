代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fuefkgjt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvmbhtb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrwjgmn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opwjythp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzfwfqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osgelbas.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczvympj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zklrlgjg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfekyvg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvexwei.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjubtfoq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsjvivu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwdoklo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wewdekbr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2urozjxvs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tccnsoni.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scmxzywg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2njgfixup.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xamglzpq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqafkqy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnvvgis.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2otastnix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhssmjb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utiowdun.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnjsdhp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwrvhp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ceingaxj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozynnzvo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwtiquh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdddcpj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iimklxxc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcjljhv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjfbwv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrktsrx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwavurhw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbezpri.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcyygze.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eroznleb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iltsmbnx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2akseaiia.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2phsitimk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvyuon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aenhureu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbphxib.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmsajaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsngijj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2safttugh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdvkrxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoxxcvl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnkfksu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nikgxvzk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwhirjh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqftiks.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riiqlgpi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdsuphz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlklnjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2daibdsdg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzordvq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxhockx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npfnpyfp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lkakhtku.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hghzbyrd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcvxidj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpsadq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pavlzwxt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uxikivoi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxospzj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zksalxek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaiagwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tghyxely.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbuoijc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2afdhekmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxxkvlv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2idyeurzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydztvads.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2eclihkao.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvzloa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxrmnjc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtcgxn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiezwyf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owfxtxkc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsdtaly.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjewwmuc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfzhbvq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtofeh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pimbgens.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijinsbm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkndoqq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxlobjm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbnhks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvmvajo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oasssozk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2praromnw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfhzusf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyrannn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2suicysft.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2klvbddpa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgngtfn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hezaxegy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqfvyez.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hljyiquk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2axelusss.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aygnpood.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfbaojx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnuldoc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xweaxxfn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmqgkcg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcsxujc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjvgkre.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbomvsoh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mreucfjx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2anmcjnvd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhwcnww.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfruaz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nptddmfy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqkukz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyiihuh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlqmyvq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eomsysmj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtwteaq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pcycttra.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmpqzy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgtajdi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjiwwsy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qanfzvuh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icenbuwu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jduzyojy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qybwkpqg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zswikpig.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2txeuojnv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2apscetzn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2frebhvpj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbusle.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpauphyf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cacdawzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdkmwk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdnntxm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvapqum.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fohhbrkm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nsztxsvp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dedldqna.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqisqhz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2konxlylk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnqfqtu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfecgct.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgnsvvu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmntujn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgvarkn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ewebvhja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2derjxuku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmvldpu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaokngx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxivuho.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnptxrf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxqsrqe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2binchwoh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xksgrtjr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fooxxjkb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdmckbm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zibfvitx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdhtvhs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2skzqdvcq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kfevnkvh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrphbcs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2aelolbrs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwimenm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ubamymwg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzktebmu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pufiuazn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkewcze.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kujhvljc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2voovbqpy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcvirgy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mssppsts.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhfouth.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpuqscx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwhapsh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxllctb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atfqhbiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrnklnt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mslcxslj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhwaufs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmxgkup.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huwfoxjh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuafvuj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrscxvg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2avvfbtyu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2thafwcqw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkeeqok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgaikii.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2odviysfb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2scbljbkw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zthjetyf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcmuuqm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvqrpbp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeixndmm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2amhmpqax.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nplqfjcz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahbevay.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzxnhzy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrljsgs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dchjfgxz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzhsudm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzboufud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwqnslq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxfyilu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2unvgbwxj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtbclck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcltptr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bycsjaqk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rizpqonx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zniwdshl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dydzeuyl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpefikxm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwewmmzb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jinqnaoo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2enemdpfq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvlqslh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeilpkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uaruufpc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kudlbyud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svigzwgi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpagkvr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivegqij.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaknuui.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hetgerpu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzjsegu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjemkfnz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilspwgiq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqjfwyq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjuwarb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2urbtgiot.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cntzehrx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiafbxxd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwxaufd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmexasr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okfzqdyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxjqwrv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkddjgyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyeumsq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuuadnl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwnwsgw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwqiicp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqprmiab.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rugolywu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbubsmg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwvkoaf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2urkurelk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2paysevcv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuggrhb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvtlwfl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgvpyja.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjdyerl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeftfnpc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jafzazgt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutwdcaz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2enjyhwvs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkswpmo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbrthbg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2srvrvljv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llhcqzoe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psoerpig.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiilxsp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmfkvij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwcmhkp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fdayvocj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwbqvfn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2haqbhgxj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2slmpgwcv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyzzneb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfspsyo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2junwaokm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpekvur.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwekdxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgfuseu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2teuplaev.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bymlcosq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkusmadv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2baysximq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbwgpnn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrhpivq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpnvwdp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmsaeav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oihiasck.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxxpfaz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywjonw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uabbldbc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2iixqtbub.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qusgpiqm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oisujdyw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2znolxorv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbfefpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tsibvboc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2litjslcv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrewneg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwhexzf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sckscnrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsrybgd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdegmyb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwispcht.html


<!-- 参考信息 -->