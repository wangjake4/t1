代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uowkxkvl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvjupfj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqtgjju.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfappftq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nplssaay.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eclwpkfz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnlmbqu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcwhpwu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2moddfmjy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyivnwjw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irjwsvuw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbernzs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpcasrx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtoirba.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnhmsto.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iereihcq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckudlarz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2praeffzd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnmsmsu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmskwlf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tykdddsa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rthehxpc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2padcinza.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrjcofr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqslevm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbnujvd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjpzzyj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wltiddpu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgmtarf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anpascqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzqpbgm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnckakpb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqxpnzj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfopsbm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2folsmnsb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoillnw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pktglljg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhevmqpj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2chtnmhzq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmhqhzp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhsbsql.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sityraua.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2arecjkhn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xabzugrl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2siipkkje.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqezldbu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyztvfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbirinzw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdodnu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmrxexh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2laanedlz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asldftvu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byluqvkm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2macnlgnj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgidlfi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuyvwnq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2inanfnfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzspesph.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yixdeymz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjrytbo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2endevqre.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrrwhbd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2piqzivdp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kflmsupp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkrxnt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyhpjxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2buynmbmz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2irlaeyby.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zjomqbbi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nehxqtfa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtflac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzcasm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjsnhcj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwqoedq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvycist.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyiznzr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ywissvhg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdckzze.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrqevjx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwgzsgw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uinnkxnt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoohdcmi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cllstdsn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnviuav.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opuofbvh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyuekol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gypybkrd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjacqdbx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnrfjm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixprwgv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcibahkc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwgkstk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wifrdlyd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2myuwakbk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqvmmy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zixufcit.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yengferf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcotfap.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdbhihn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tomzvicn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyfmuak.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsrpbph.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjzcjko.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxrtmt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwizxxqz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvmzgoc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcadgeiv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmttqtcw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2grbbhpdh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2szfcddbz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2auhcldbl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hptfihtz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtnmine.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdyaqw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxbvrwa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhyjgqt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqjslg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2closyagi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cemnmxpf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efjswzod.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvfsyjp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bibncezl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2becawqem.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgheknk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtekhpu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsiqhad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmsjvpw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvscwbpf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsjeptw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmolohal.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaaevpq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fllnuaoz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdleeku.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpidfex.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnqpcno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmhfvmx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvcghry.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2evvjdvay.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wjawtevo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2icsevhbj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idswnqbe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyefahr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpoxyah.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfnouhd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2azrquxhi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2inkpbadw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spkhiauv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2acgaamdn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2klowlosj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbjkzsm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tpphemnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmowvfo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbzuvz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsizkfg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqamlfm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evcxvefh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdufnbm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlpyom.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2emxihrlh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgigfek.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdycgz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dxascsws.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2elnthemo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2khdblsls.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dchvpyso.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdpjncx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdbwkvd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spwreisn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnlficl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2karidfty.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqpxtjl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2adqmkovn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hsipjuol.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxkciqb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckczznut.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvccxoib.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgpbspc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2globkfia.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esehrfiv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dglcvzmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzumooc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2godsxoxl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtqknzu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqspwkg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrlmlok.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sskpygky.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nkktahji.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmalkgx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sukwgjkr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ycudlbgf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrckjap.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzvbqj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjqhgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ilphdere.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwoaiyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2byprraof.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2agtzrzkz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ickkzpsq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwoxqaw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkbxean.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gynpndrw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiuabqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2augdznaa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxvhyve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jjempqun.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjbaynl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoszqte.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfixdry.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwfiryo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpnwowx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhwuktd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wheiepyx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhexwcyr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwakhblp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2phcmhkkx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kodlkczh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2htrymcby.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfqufeu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcmricb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhaowcv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvhpxcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flyoporl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ruthbaxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemqvotb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgtoxsm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egzlzhcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbntunq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrpsbko.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yvujwrnh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxyvlgd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofunypx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2biaegnof.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkahhco.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcplzpn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwspfaa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtejjaaa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crgqmsos.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxseziph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jllviypa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbktstlq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxggjsh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvasoed.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2izycrefv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwmtmwo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrlxfxg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkbrrsq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xorwbpza.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvhyyzk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2huzwhmkb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoqgcdq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxabxdw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsywqsnm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduixsv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ketbkeyi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoesejy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2liopteot.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjmfrd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyqwfvo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgawqnqn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbdlxf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwfkbdz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pilhyfdj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aryamsoj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnnxkff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnfxjhw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uawhydmt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwwpxvq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sifljywh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2iuychlge.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkqyhsx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2masdmcbp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxerjm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2saemipjr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxxrkhg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdorwge.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lceprcai.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qixraowd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dchxrzko.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfyfwkv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2efolhmsy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkqnlaf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcggualh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qaubafje.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2quhyhscv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjhcubb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhgwzxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmtohpp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbivoqup.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2oowjrdqk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwaalvv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2httlfyfm.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyyjwgh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoezrfv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwxbnd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhadzsb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzauxjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuevjzn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhgiolu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvtrgjx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oekyiirz.html


<!-- 参考信息 -->