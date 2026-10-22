代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocltovjj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbqivpg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2omibuvxq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaqcejl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffdndkn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqhewdh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbwxdwt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2onhvnaxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbgxdyn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bijvfbbh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jimgrtzy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrjxarv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdilzyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwvyouf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvopchnu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzqwxib.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxrlauj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzgqao.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzraogx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhoeezu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2djjgdpwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkjept.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkisnxsk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmbfalb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eggeauvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqbufgv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcexjwca.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjcdfvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccejqdkw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sswjefvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaiuhax.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icvgpfrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szepxxef.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsahbbna.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zextarjk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaajxkb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpdhmke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siighnrw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtmnljr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuqrnlb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2umswyysx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlkjflq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2radrkpij.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gmydeikj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhnzxrj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmpefa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjqiwrj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pcebxgby.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2amaacien.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uutzsltk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2luytdewy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2egsocgoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2higjzmwt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2otynowxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqbghai.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdmojgv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kopwembe.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgqtcnh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oueelfzc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxilvadv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtziqmp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2owguijwp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtxktud.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkuwuwo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfuqzvk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdiddts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swvixpfy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdtuvic.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oixklngs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akvbfgtu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwltqkgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awnnlxdq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woakemdh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbdwlku.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qujwnjoq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jptfthuv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtfyzao.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbeozak.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtnipot.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bktawvdx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqbaumz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hotrhiuu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpeznv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrbfai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhkitoe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotdmcup.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkeutsi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfhjcpo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjtpkur.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krnlmjzz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioadozis.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pljcaglg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zshvnxmz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpazbe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbktlark.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efaztkbh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqknzbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2novfajgi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfpsaho.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvmljak.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrelgze.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrxthnx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnyhzxe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtgddyy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmrvrtx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnydded.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tcilhdho.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pizjthry.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufelwfue.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2drbvzyyv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbmvngg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcswzle.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbsargj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2goebsxzq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmngmbo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrjfzjt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxwhwpp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lznzofew.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pomxhsxw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rllmwrgn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eltbzqik.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsxcvlk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxdzilw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hegnxdoa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtdvkdf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfaciuj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pthqscyx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwqflgg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbcsnjp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtfydie.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2shmuznmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqyoqob.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfizlaub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xynoycvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zohymouy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrcpsms.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzqowx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzaspcm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmqprsy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2buadnpib.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnhgcvr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2voffckkk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dwggzdhv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoqzvcf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zoefwtai.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tblmbsrv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dspsfqau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omqpvwzm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhdtxdo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgptftq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crwefjoe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqztyvhm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fraircnq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdilkhn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2coipbpmn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgkbifz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prgxfagv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsskxren.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmstkjrm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjgnvny.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdgliji.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znhalzgx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2toudujjc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvdwkqt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2omututew.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2prkckboo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpcqmam.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qznxrhrf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2syznlylc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ehofzamh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoretznh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmungvk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxhdxhr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bixccbig.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrxbwqp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqkmmny.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdqivlt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpfkzvy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhqoca.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxteece.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2eozgqrtc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uchjtnia.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhzzbgl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzcbngc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2crbilxut.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2miuparex.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvsrnao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbbzacw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzwjxtv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucslvhfv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvncths.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2inqhnvky.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2aabzjokc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjuzpzp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2guptfqgk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2thpqyfwa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwqjkal.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fobyemgj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ssroifmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzhlzmn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2msantamv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdtuqtb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhcpuu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmmiwec.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2soddrfxy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomuepej.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbobvnj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhacpwvs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhzlxic.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dywqburl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrwjvod.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2copbyohl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxumtafo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkolumd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rahdpwme.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvbvzbl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkewvwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfnvtcr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrhxhiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaqqwhn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lfucxjgv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnidgnsf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuysyfo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmwgjec.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnfkhzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdrfbjp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtfhnhe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2rteuicsi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjpkyuj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxepla.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvqtcuu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpnixlc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsavpgcm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfwinwd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plvzrfcm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvstxjlu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urjasonz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmctbdqb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvmxyyw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlbkmtk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiifvsp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolahob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdgkpui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuisulk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzlwvpv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhcxeli.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjozytk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhqeyrw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2etphvezq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkbgjde.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rovayajz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhevvdn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2etouguxa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuftwho.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtzsvuc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qeumvbig.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eignxdlj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2waziuaay.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dupbvslr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhgtvqu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceykxgqt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfiyhkl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wicczmbj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ismsqmpb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvybvnk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pjazzizk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rerifkmn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtricavh.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uisvgmsr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcpgdrt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2adkhcazp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbkyegx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bswuigfk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aovmmntf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpdlnbe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tadysavb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2szomjkkd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2weasfsbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zunstezo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myykjgdy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnzftid.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2owsuflkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwiebpw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtktbn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyifdeez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrygimgp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kcagbdzt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvgxvwy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuhcoub.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcwwotw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpsqhwz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcjnals.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edrwnvkg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckijauuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxbhyzy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eklywlvz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdsensy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxupttgg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvhgvqb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2voehzocz.html


<!-- 参考信息 -->