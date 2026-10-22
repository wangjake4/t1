代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itiluyou.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksurzrpg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrkhqmr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vixdhhgi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mirnojnc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqfslsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtgpemx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzmaubb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttipkhrd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pukywvzm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osmotlla.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fikrrbxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvfznzu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weciepsk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwqsawl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnbxfoq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnjceea.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtpfugl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeityqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvidxpg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwbunm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyovymm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfzjsel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hygtlffk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2knaupgti.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkkazlu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvepjzb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmrkyug.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlqxzso.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtnbdvk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwienck.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzblkbrg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbasynfa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxobuoyc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfyoel.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oftrorzd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwpxplu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwuuhxq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwfvnyt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjhfdcp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sdewmxot.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqmcunj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwjmsul.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acfkbvgz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gleiidih.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeslyun.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrfmpcz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhtytti.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gignrwqc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qddkmcsz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zafuafqd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qofzxpwe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reszozhi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oapnaunx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjgqsos.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cecycxwp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2egarkdim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnisrcee.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnosqojn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msrxutyh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdvpqkt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrsxkxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngwivzm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhbaekz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypfpmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchbbmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2odsvdjnp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xngftpjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqxbbnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ksntkpzj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvniaeq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzilrcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oszjqvvq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdhjlhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcptxflx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2urqlalmg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoyeziu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shidwmgu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgipxdum.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiqzduc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vknwrnxn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2llaxlmyk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyrxpzs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jokjfazq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wottmrox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hccremoj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvtygxj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cawhlbxc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glchyiem.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnilged.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnucmwql.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzpbdpm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvheaox.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmmyon.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rntfhktd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwzxlxz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eemaxvzr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjsuzxk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwixehx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2izqgavew.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yidlkbbv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkihaojz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odykvmpt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ktinzzzh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhcgbjw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwhhgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuorlbh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirxkcfq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyhyivr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnwizui.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfzxgg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2prabxeqg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvssgbt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnbxbwv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdfnzeq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfkvgfv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurbsps.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dverqxkw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bamfvlns.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpcsphx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2awahbdlo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oollndei.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqljevmo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zronmgni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwljgh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcocqxjp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxnghcf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qevlujrn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwpkvqa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyblutcf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjskxbah.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfpdlef.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrakpwr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nztxjmou.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rshcomde.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgsupnn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2evmidvoh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgeflqf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2watlzdnc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdkobnf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpoygmb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mguwmufb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxwfzsa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlxlohd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnkoklx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuohrde.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkuvfif.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2drtstrpc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rnatmtjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmobakop.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zpypnkts.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dffnrjyb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elcbmzdf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgvlyly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuildgy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwknwcai.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2drrlqwwf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ileqvrwf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtpotsh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzydxxb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ibenecwc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlseogd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojkjeu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2trhvabdd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcidwjt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnngbdq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrostxk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgzepgi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnverrxg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtylxut.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwoohxd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cejdlotv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjxylou.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkqevfs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvhuxnt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxstghka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqtzdu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlrjzrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzxzhdv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drllravc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fomqzbgu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdcdjui.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nejixsvr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpywewqe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxholjx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvpunba.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnoyasb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eblkzede.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnzcyir.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzavurl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2relkwakv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bldgazbu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uiubbyht.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqitxwup.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjpufuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iltpigti.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2koxcctqt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoecmpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbkzyun.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2acivjdec.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoydwblp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msxrsief.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqncqsoc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlwxkyh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbswxsz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tziorsdo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxxasrs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzvzadm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhxnijx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzmscfh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ibskwtaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2egyukvzo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxilgsmw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vndegwmm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkaccwn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2naapixet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsbaypr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwcbkj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kfggwaib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxdbyet.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hauwlykz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrkhjzv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dktzsarx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2usdtewnl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yadkxzfe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripndkeh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmfrkjy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aywtpjqv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjzmopx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuzdupl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnqhhk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2divtxoet.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2czyuzsll.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyowfnm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohmqbew.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhpnsvl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scgudqok.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlwqhfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbtaubu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkthkac.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxusrl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcdjmxo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlclkyyv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbsyboq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmftyti.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2amqpfaja.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzvnfkl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfoavrq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txvcgnyo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onxttwff.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzoutak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aubrhnxr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgswvvvt.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmtlniy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2effjexxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtiijye.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqqqppy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlzqqxy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcivoipw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2skpeypqr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwjmznz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrplaibk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaakfaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xymgxlqf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxmjojl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwwogbt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtngemlu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2agzlboop.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zmogmdlz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxdbbeg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkiuqjo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtspbtr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnjgwfb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjakgddn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvjptbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsjsjnb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dumwyoll.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmvznor.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfxxrrp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djwocibo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdmicze.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptetjcvc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uilpfsdg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yumimxhq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbduazkp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cdppgesu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2shgvezco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdascsb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkfpodt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqblfgf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwehvoh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gubtligl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbnsoxv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnoanak.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edswucew.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxwbdhu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mektokhy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2stlvnjqj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cccpshkc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyxgptm.html


<!-- 参考信息 -->