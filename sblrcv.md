代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jymrnfdn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pryictkh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2soiqztlb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnxhwui.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoucojsr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqklxro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hionzmfj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlgsvnr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbobbidp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qieirpsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2njdaqfnl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcyggjs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvgfkct.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdimdm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeiavze.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkrguad.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjmlaoo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pldpsqgr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcgnjwm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2izoanudg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iayofeas.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgrdtpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjmlzuc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdukjfbe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2izezcfuw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgukck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owmqpjir.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcuvtpf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btmvoybx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtfzdlk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvvskqf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoarbdf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlotytdk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btqxoevn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhopmrag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eogvyqeg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqsjdye.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sskpqxrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcebxex.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2giqvqqxm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaycgcg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuskxxv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2siguhsnk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqikkl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2isumqteb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqexnjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovklwdws.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrbqnre.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2iuchtsgv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qsooqfpp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2evpjcfkb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lxozhywb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnybcnot.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iorbwndq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjeysfg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2huzworou.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nbltqejr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoabktz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqcxmhj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfuwlfr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2resmpdqk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpqeuxo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbpdafp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omqhyqht.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwqley.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmxpvlk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unickxoz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2towkaymw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmqgaoj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hawloldw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqytgixv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvbclcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkauibz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaxbfts.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcicglxc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2agiklnmj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onysizup.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hokqbcct.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolskkfq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dhenuuyg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqslnsie.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckynqjwg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jkewglbv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aztjnbxc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cweiwpmq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsfdyfa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iighoxxu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htuihzaw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2poylcjll.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvecifcb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlhyynh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sstuuild.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2inbgsyey.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsslpzqw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrhwrwy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoiutly.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thapkywc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uaabuweg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hlubefxa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwpliz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xpabbpmt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaiznku.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsvewez.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmjglvk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agqatykg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrykfbgz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bdizjean.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peciznbn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bphutkzi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2opsytekt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ragunqbl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejseenzu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrixucc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcjivtj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2onvrivea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvammnp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pteawvcs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgvotju.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rdltvdyz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdaldrf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnddsfeu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqojrhf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achbdwiw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvvhsxu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yslopqeo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2almdegnu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdcmltr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qydzgyyq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuhjbzl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewjnfam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxysgfh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsggxtlm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hripubrx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aflsyvwn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwzzsbg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjpzxnj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ygofoshc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgddpegp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwcrpcb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hyunkdby.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yoskhkwf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gkikbdcw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcpuxhg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2phjfhbsn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mybicwkk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sdivfdwv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2czshjnpe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsokxtny.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropmksmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmlfiri.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meaolxak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvylixuo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkvejxb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnmtbsn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oogdwdpq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcusfii.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsmzmft.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiswfawk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqebyamt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdmlzur.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvroxys.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmoiomk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdjjswq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvjyxcr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjrbqas.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwllvdx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2prjlluml.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwbhhyi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2snosnjtr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uaplpdmm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2arfnsdfp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vggeigiz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsnmdvh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2njdndqkj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wonnndyr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecunnxex.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyfpaid.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzkycou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatczwke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmodykd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbjjft.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ryklrzjk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fruytilw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npovjwtr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yefwmbga.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpunwyrg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgebrnmv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvzadwd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmelljo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavbqmtd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uunvhujb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwxoxtx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qauumcac.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwebmpz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2srrkahos.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxbbwfz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfzgbzz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jufhebjb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wokzwocr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zofdvbdf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzvhwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amrdfadg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgfrwy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrqoneh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejufods.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plejlrxm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxgmbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqvxzyg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2scuechjs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vyksntzo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosgrrnt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2czgvcban.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2oydebueb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrtwqt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrdorwe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyhpyb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwbkdh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lacexana.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wivfjqib.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpovrwd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqxcqdc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdherern.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwucozbj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgaukcz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdxubdo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qptzznbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsmmmnn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzxvgfh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2reqwqhok.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqheogqe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2szrdrurt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkybjug.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zidwibpe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2istsqnob.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxosipts.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yincyylf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aniybfqy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmzbemi.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnojfi.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tffsqgjm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mecfkiym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hljqgvmw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgehzy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlvmgwv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzadlle.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsygzby.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iddgevde.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zadfqtiv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2clfxxjdc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uioufhrl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaygazh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqyeqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyukxge.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2plccsvxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcoqhjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qdessznz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iimoxyuc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzsurks.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmviomdr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgugymin.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqewcvoo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2puplhrsi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzkfrqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnaorwd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2plgscrpk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmkzmor.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2npvhqbuz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlgnlpq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2feuyntqi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkomiqlm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxxcmp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxfhmkz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrktwcb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhmdekt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2msmbfvdn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2geoddzli.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzbwzlv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjcqaec.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2skambidu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twckhvbp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlvwkhl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqpyegh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2axpuzwzd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cicuduwi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuugmtc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2izkghufx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmgylrp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jvepfsjx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jolpgtas.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2huiwbvbt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqptucr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wofaqezw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vutjqkrk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzuwtfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flnmhosp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcrcfnu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvyjnqz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2elszsqsi.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkepdiq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbvlafn.html


<!-- 参考信息 -->