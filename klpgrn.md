代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwafexlt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iiggfebf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vikytwlg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2grsmjktn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2awiuurmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojjdqcm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmgittb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2irpstdtd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxupeax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqnwhvx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgitzpdv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcpupht.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibojrkgk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqitft.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqsbxqe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2owsnzvfh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jvovyanp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uksghkvm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbawoyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zejbpzkp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2trresvgz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuavoze.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnyrtcl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaudtdx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2niboyjzj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrrqexa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxwhcql.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcjjyli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqqnftl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oysftzrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2adgtuwre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgprveob.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdokeamh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkadfnz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npyxgrmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdlepqt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtfibhd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybujvtqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgklqxea.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osybtenh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhvchz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaynoig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fplajyrk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyztude.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdzwywq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzsxjpb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbguzit.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2apxepvyg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aevigwxr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxhcnhi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpswibbf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hygmavyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjgrzbb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkpcmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eesutesg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hchoezlz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iirmsakh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijangei.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnqyqtq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amhmbeur.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiemfzf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eszdbtsg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkthnnj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuswsbo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggalrkja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxttouux.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaccdfs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsgnkwa.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njeoivvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfxxzsd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcmfvd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nazwcrap.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlofzod.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2whaohdqq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2obildxva.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmikijoi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkokjpxz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2landfrkb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmvjxgx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzfevhs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyswphyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyiihhz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbpsdsg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uomfrser.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cttbpgyr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvfmpc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kumoignn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fropkzje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyruddf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdhbfdq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2actrzozf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlnkdk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwsypzo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okvktnpv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxbhav.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgueziam.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgtfvcq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmqhodf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xruoikum.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkheuoja.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeukxmo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbbdof.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzrehfk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utczpwpe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnbiiwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjvbowd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqvdiww.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvgcsor.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpnjrnn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mypewoie.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyrbhfj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlruswxm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvjdcdd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tetwfqfq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qssnudgt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uegussgj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vvixeoss.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcspbrur.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeifqgr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhgsxp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blmagcwj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsyyaru.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcdxjyx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmloeihm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2niugwgxx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yatswani.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kghrlnpw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xaewovyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2txrmoove.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwwuysp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fzunyyyf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykatnso.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzkweiu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntqlpnv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmptjnm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgirxml.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fesdnhxt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oonzwnua.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyixeco.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ayweqdlt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqgiika.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqfjxfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoyrbvq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2covulhcb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2febmlotc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bgayzwcz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzgqzfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwwgcj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etxvkbnm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirasfyy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdbytid.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymabsstx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxvktts.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hogvxeji.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgceaai.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nddxazrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vszsafbj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgzxjrk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oktbqnle.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiktaxox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yntiduaj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2relyynzo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtaaiyy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbxdxhz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsimjz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmtwdrb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvtbsdb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjwkel.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhhfdrv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmlqnwg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywzoybd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvtvqzt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpusayf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtepasc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2eywvfzpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbanqyhp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ourmlsrg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghunmals.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wllkxdzs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2htswdcdo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzchjm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtfdwut.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjooqjuo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yesozsjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjvbxuq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pipirpar.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyowkgr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixomly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lakkzjrc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuvktfs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gixumfyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2eafrelpr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfbidbw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiwwtxp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqluvns.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnuaywr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfliqz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuutmfl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxwbctz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnydwjzr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqpzfro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngipxhhr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeoyxmj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrtgcv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaumttn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeinxhvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnegtjhw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veinexeu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbnbxfj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyfohqz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwnitsg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbsqtmz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrscomhf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpnvfcw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxvccf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmuiyse.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqqpzhl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbzjdmf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzmkqkd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfiewon.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzxvcdq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2njkcinen.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2piwbqvbe.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqswjei.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pemvtneh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2swxrygml.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrjtoju.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2njckiacs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugviaubn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmzdfxi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqpuhn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uimxmrox.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnyvaz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgzqic.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsphsbw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljkioep.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pregvcqs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyryzpad.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmopkjej.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eclmzwvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elrjpmvf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stexkvzl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqhluxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srvjkiyt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfddlvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqxfuhe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chnxxjez.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2omyqruvx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbauhsn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcuigpe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cvglvvlm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rllkwakk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2njeknrds.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrkvngh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jerzonbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsmtwjz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iorecqwi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyoanhr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjymokdy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tspwzfrx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpjdudq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeyouvw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2crhkvuxb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xojddwcg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsbaxer.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpsucwo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeyfjil.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqjxenj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdihaxu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajflftux.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvzuhd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rugelhvh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmdzbz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcmbuzr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdgsxoh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmmirjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmndxel.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2llwsfrwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunjcwmy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tglorayz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnkjdzy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfdnser.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hscghszq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqnanlz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2alcmcwrd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqlhpsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bajpjrcn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2epguznnm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nblpxuat.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsnflwl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwkttgd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2szmdrhez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiviyxno.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wejufcld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psmgjkbk.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2neqltzph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaxqgqb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaruikog.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyomfja.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlcuyxo.html


<!-- 参考信息 -->