代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrgfpjh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvevtte.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mscddzaq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abooejiy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fngocnks.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2veutzhfe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqyvtdf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizjygcn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqaxsal.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxanuuhw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqywro.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpljyux.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhpsinw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnbatxc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyzaryg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uufknbsn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhwncid.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbibvnss.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2attenyvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpseoeki.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbyrmv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjtrikg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqrcalr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxyloha.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjvdsfw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qohdzmld.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2peumktfd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrujnwp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2carhibti.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbdycvj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2btmnnifn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpbasjt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ecketlgn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jycdlpuy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swboygfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2efbnrkfb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsstranf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvxsjaj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuiwhaj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnpwemc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqywzjts.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dicydwxn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgizkni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgdhnjr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smwrtrlk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okcqsacg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rljxxbum.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkwqdit.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcvlklr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrmhnxb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pondfsue.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2elekvuxu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxygvjc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pesbxwoa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kuubkmox.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzbgmeo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmfjmpl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lciotwqs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fymcnvak.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eibhzfwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbulal.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdmsdhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klximtbw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeczyuq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqxlrht.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceujcwlk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zspmydji.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qipozczq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgagbyyd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kidyalwc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvvxybb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpssjgk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arvfyyrm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mboihtex.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkjnhpa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwqcrsw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjbnlca.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnrethk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yncpyyws.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jagmdhsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2novwhkto.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgtnyvd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnrkjfz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2krjisyrt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbytmccj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqigqzii.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvefkdev.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2swfdrzha.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hztacrcr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxknsdzx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrrhuai.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwcbylv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noggqkyq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkalkqf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wblxkimt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukupxikx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdmuslh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzxmiap.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnqbkkx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nyojdmkp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vejwcwdz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxztbgwl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgoxxrb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eahkmniy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyhxrok.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dksayjca.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2folmbipc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atbjyrtr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pernwpaw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeweecc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtsnmbu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uellpkyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxpalbh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlogeg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwwjdvj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmnbxg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsukfdo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efmvpvmc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtwgaue.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vttqsijv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smjjttyk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qukojkky.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2csnbhbrh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdkukj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjjjnqp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbikberi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lusgnqas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2entywsfs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nffuxiia.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiqatui.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeljuiif.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhvdlwv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjlnfjj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwitzenn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgppspt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2clttwkzo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vphoyltv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjseuryg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zbynujjv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvziilcf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlzhpnv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2arcogvnc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjseikhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlsbvsg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2txxjahbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2muwwurpy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvkxekp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uroadfjj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdlhyic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hduwygvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nofhjvae.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2srfosoju.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvtjfci.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgkaies.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2obbnyyzo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshnicoo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxeiwka.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoxxmji.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwcbrdd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmzwvcq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbibsome.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpaoqev.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmmqnzi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmisvzr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjuvfeh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcemznf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutcdkm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbpvtii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkctwbqq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrsyny.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkichvw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbdggoi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdzejjq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fopjshcp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2njrhcops.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpckyvp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwxircx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkyafkd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2henuuwtm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ntozvzfu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ruldnfrh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2esmgyreg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cocfqykz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2psmyroni.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2owcfnhvp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utojfpvh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmakpxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2alpdyzlp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2epatxpbs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2recpxdzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpchsqt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmbohyx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlxscns.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppfaxco.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryafzcit.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgzypbj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsryjwl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kguihrpz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbazlio.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ogffnfqe.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvctobr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpjhpy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbceedl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtjygd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjfhuox.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nllsyosk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsdvdju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlliudy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jktxflvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oswqhfgn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2emtokklb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2doapwpsq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbpgpic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dedznapg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygudukqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskfnozw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxeloay.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyiacoz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkcnmdg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vknxfpgo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2psjmszae.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snghrzdh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltldqfqr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuperqk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymynjdac.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaannoq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtaegir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqinfvw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxxqqzs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtmsmqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyucwtzk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnbtsss.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqlrfda.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcoekwi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoumodl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgttivt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kssveycf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbdiqy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwuzchs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgurvsz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcoosjd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjscwsvn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oazvnfsa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2utkqaodr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsvpvre.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyhtgmj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqrqkhu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxniave.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2anuwdyie.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgmukoq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vybjlngl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxsizwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuckwvsq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqhlypv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgdhcqd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tumiylim.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hunqmvui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhqadrg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wuctmins.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdaglwl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2scmylvjk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvffcsio.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgykizni.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cqamrdgp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmetinr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvthndj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgjgahk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsaglrh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzraesuk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlzwlji.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzwqbga.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkpbify.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdehegvq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rjckgwgh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2juytugxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhepwcb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzrienk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqokddw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylczcrdv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2heleamli.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkzfbdq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoiytgt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoopbpw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2iljvxjxo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqavdwkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhdrhhz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwzxbzq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuonbcj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyqexwp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2afenchum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwytmkom.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeifkqb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vomfpprc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsvrzku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmjppth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaahgaw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdxovip.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2udllsaoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaswfzrt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2plmqamkm.html


<!-- 参考信息 -->