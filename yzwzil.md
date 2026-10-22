代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fekulntm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvxcdvc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2huwulkqr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygazyvhz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrlxtjg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wstnylcw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnuqzwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2slptwwca.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2byquuemb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgtmjtm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2asrqpxoc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrieipi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgmrywb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sibtqfcr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kidgpaku.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkjlfdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfbodrj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefexfdj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzpzmxp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2envbmtsj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkftzus.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwniprih.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzmbpst.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzkhaxo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwjtzkk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqwloqa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2radidzyi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pithglin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xabfhonv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrzxlxv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjhzqhg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqupxltu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnffqib.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kwduhyhp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkugngmx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtqbeqi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoncfjk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoqqmyd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnsslga.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxkjiqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueausheh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvzpuvd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuflomi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gswcjchl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eicnwcyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhlqazb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whbvxaqh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvfoqyi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlvqsab.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtwcnay.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynvmdg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jytvfpra.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyysmqun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcirfhjn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2peaopnpi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcuskef.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuybone.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2racpnesd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2icjvljgl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vbniqlmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsqoesy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpoomaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtgqmbc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeflppb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gifusnvg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkqycaw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpezygdu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzwptiu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnfdput.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdebwbkg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvbgyyv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axqlwhcb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xahwtmhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtolwfg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpymlpkw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrdtvgf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqefhgdp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbehghg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxbrixg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxkvdte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpspyxni.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqsymet.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzempr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wawheaae.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pblcoinr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyoovoq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbomwdqm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oukdcxbb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwvczwl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcqhdiq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2diyhgfwj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aporogiy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvtpife.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkefekao.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmxyspl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yibcmdnh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiigcrgm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajifszgv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygacaqh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2okbaqycs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjixwen.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upqvcvgj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iclvtsqx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsxguth.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjamfug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sginaxvs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsszvapl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dguxeafj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pntpaope.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjlcxtg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgnuhsk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biguhpyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvdwsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akinamvz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2olithkij.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uaorwlhd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrtmhyv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmfhviv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfsaqql.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxdedio.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2swnmizij.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzmfuij.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmqpgxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsyxmuq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzaomoq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jaowzfko.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vgafebht.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ewegqfnf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhwfrfd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfdylbt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiwvmjo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofdwrq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jygieaom.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lktkxuxd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcoiav.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gohxoyyv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtokidu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugncbazu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2grwnmqbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpxqwnd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efmgzwec.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgddqcta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbksnbjb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkglzgcr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwcpllo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjsete.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbbrqw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlpjtoc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zyerrrbb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhybqod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikgfew.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bfodfriy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwktcwr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzoreqx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fiixvkmx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuhzkjd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veldpvwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yikprsov.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yccvsxlk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgujlhf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhznxwg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkotnyi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nryzqyoo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qunhczwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkavsaia.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcavawvr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwcbqqx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykxfgcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nojzttwo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hshgygbh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchyfhgr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdicxoz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yslggfcx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzxftd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pafatbdr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnpddzo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2puvjsrjj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxoxows.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2syvmwjmm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nveclyba.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoijkdr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzphzso.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyhueca.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwgjvzh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxflhsda.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgclygzi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyskhso.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnhubqg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtqagok.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuomhxc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbriojqa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxpdros.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2etgtmdix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xegkxrcb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdylhuo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzdosbc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxskifu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzgmnwq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cdokaqvq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvlupyf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtedekh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpuqgjm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbwhask.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvyaqdn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvtqqcu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lohutkat.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrzqxmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckunecpd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbmnohz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwdxgzx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvfqqzz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwccvgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfutttag.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiultbo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxkjevs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvgqheo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2egktgydp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjuilfp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpekaymx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhxvypu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdstnsbw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaydomo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwgziue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpibasn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfzqxth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmogcbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cozwmaxp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoplfnc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjgcspv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hukhzryc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tctdmbam.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bczfgdae.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqijswa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pltlnkgy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2twdtdbgw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyuefos.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpztzks.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegditg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwypvqi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwaqmni.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoqfoep.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tntrraop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giessjtr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zafdzxhd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvbchcb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvjhncl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwansstu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gnspcurw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdowbcli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwklsnx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzwysc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhexeprk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2blidkwlv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmwzupd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrqpan.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2brgcqzde.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkffeex.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohmeiou.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2belaaxnf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwcgdpj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmjhdrc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2okjjijfy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npgnyjmm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnxoatp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2irhrwapv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwclgalk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2taoowvyw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmtfkmw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgojojni.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybmayr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gznzplfg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oaywmcub.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyslsyuw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vsreqaad.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvadywvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2aghjpgwa.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmmxiik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtfzknv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzwrqzj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mitjyrrx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tczzhbar.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2czgsxzhc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dlerbtwb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fknwlylc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pamyzqmz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvbvvfu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeramcto.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqowzns.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxwuasw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruridvoe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxddztd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwtzjwm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dljhkimt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2eahqhlkl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfgclzs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoleutf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxsuqk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsoytxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpajefth.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itpyngri.html


<!-- 参考信息 -->