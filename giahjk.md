代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwezigc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbenaekf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzgjmsb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdeynhp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npvenbyr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hctqsbpu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nthvdbak.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwchsrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfxllvw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eilqbwsy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjkjonw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zugxmfru.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfaurpm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuctrxf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvupjkwc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqhsffu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afeqxyev.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjeczss.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvbejem.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisqrxzx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhymqzcj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sztcvtuz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxytkunz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtwvazh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkooesnc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxemwmqh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdzyugc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfnffic.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2orgtyuhk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceunnykc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljsbql.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgxqcgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2unehskzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqllfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmmznma.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2icprbmcf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rspjmqwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mecfofiz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwgpods.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upfxextd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmwdjns.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipyxpnp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbukpsjv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jprlujoe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2smyuofqp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kihqbham.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbadcli.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqoobyw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhvtemt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2udsrurpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyqffme.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xonpugek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrjtett.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsywndev.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkaoxce.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkxdffs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjirgln.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzajqfe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgdomok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uslfohdi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnhxkkv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvkwpor.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiqmvvv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikczurg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqoereg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmelvfx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcbifdy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzngcqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpupvmp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gaibgfcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ddddopnw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkeevdx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbqdyib.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yigulwke.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmehyvl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ulujbfxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lschvnsk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2foatecly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txwqspkk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsumjqgn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnfdgre.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmcucfl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcnsllf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgwmdfs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koasnhce.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaieavn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvupcczn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byzxpqtr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkpdeqe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rltxujjq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nctkfszv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvgnttc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgefgodi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmfkgqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jytkrymr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvchht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weyqfbbq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbirfaa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfvrvyt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbskndh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2btaxrqnd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2erfeagcn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfetbex.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ohevaqal.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uczcumnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiuplhc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnotbyup.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvqbidu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzxefxw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krizcxkz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzomnci.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kowneuxe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxtbbub.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frtcyufn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkdflz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2widyrefr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjxchvm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfhloi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqvrlrk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlswjvy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sndhzrvh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcjzzez.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpshyplk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uspuzvok.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnnzsie.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbezkgcc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxgvvas.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egzmrxyz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokddkty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbncxym.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdfqvvp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nghkwszu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cuprajqp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2neusxjzl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2adtgujhj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvqvzc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvdakbf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypanyfpl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfshatyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwdwltv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2envzelso.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwwxjvf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgpgbaf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuzodma.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nidiffru.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwijjkth.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrfxdjq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvbuewp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2phejvaie.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjqtxfb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqqdjol.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrctmzh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uvupcxhh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtfdmuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzyvnw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixojysan.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqzglhi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcjpcn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbrkkvg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjzuhgk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrdvwm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fssiitud.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnukupz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqexldk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oflzwnoz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ayinscun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2plaffgzn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2egazdeos.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tduquxun.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgbhmhn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiqtbzt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfmaogz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxgumtm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqkinzz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdqeqjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdhvbhv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwzdzep.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgcwulx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdweamn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wccnrjqo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvezqcb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnpqmth.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfykfvw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwywfaid.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeknpxe.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2janozmgk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2caemegky.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utioelfj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnzhqyk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxqnwdg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2snvektoo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pmffoyjh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpgpvmw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbygodq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtzvfcz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kdltkgwl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfipjup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvqucvu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyzgrda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjscbrwn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpefuqz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwhuyoa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqodvbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jglguumi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2biexpejk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2khjxotjq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhahciq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2insnqyvy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjjoait.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolntkvp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlxidyw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxxlfql.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2emidwtzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioauogsf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgsqmvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bahjmjvd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxbduny.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwfqahm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiimcsh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnshohin.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2frkxkxus.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mziptkqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2znjdvbdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdygkuik.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwlgisd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bneawwsh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbhkdfj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjunkvg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkwyqao.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnpxab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zznztsoi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwwcpat.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmcryen.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kazymyfx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkeukpl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgevutm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xogvotcp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqcrawr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmbakdg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfpkedr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfcbyud.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbygzih.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkcezdn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuecavxu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmgdzrs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lttmatbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpnohlu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jogzbnbr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2haqsksbc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lozbqtrz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzktqfn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2iljvkbpq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvpqjha.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sciqvjwt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbndnaw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzdcorr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyvttco.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeqwkvr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvulqhf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctlkkkp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsyyrze.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlmwuks.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqfzxde.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgupttn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnqkwxf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obizbavu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sszpvxnm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsownqhk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndzxrwh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuhobhh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdajvzth.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmxrswv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uetysjjd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqbwukg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fobdzynu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmbnljp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzvnbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejxeuqk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgobgbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfvkosy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjmabhb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnptvtld.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxmssvg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsgxhsk.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afpcjvwy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoaqrff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyjudni.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqqdwoh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwgoxxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bozalbsc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgidxlwm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbunnke.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2odeboqgx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aejpduas.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbijluqj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvflrnyp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xujblblq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2upqlukba.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hujwjkow.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zztyeerz.html


<!-- 参考信息 -->