代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkebkco.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fihxhopz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2incdwckh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqyxqsu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdcludq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqwenxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzikbm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2quumvaet.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fldgwluf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqdwqpz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozepjajr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uynftxai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqltvzku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veozhyje.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnqnkcg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xodrgwnm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plbhqtcf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbhwvav.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqydwoxo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftesjhla.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzjghno.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbcbgdu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpgpmax.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihatlztz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2whojthbg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmwoyij.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2agszqacx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpwfvma.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaouelkd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2retqdsml.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxuxzon.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkdfujj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgdnmls.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyevwhzx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzjxvkx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhismuta.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2carwmzfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kftpgtmy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzmonwg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xabfyqef.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlkzxlh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvzvvob.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdstvdn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfonzfob.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2moyypzxy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2czqkliig.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tztjhceo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gteheadk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htkhuvhv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adxnctmn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vswhdacn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eexnchgn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoemabo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaleljp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dplvyeml.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abheofnd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkqpdff.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrgrphy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocegtmmr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czbrmmyo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2upmbtszh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtviuukt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xijhigwh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2etxejrah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrardwld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2baktrenh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjudtw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hlddyzhz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoirbxu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2soaludmm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2petmmpeq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oigvjvyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brweezcb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ermxjkox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acvjfaio.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkilwzli.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxyqopa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqtarvc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxdgqoo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iedmyfxy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpjnman.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2essoojsq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znchelro.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxxxrpn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qswwvyof.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gglicpba.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htxfdesn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsicsiug.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqycjtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbtehky.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqmxizm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sngmghmd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqkcudf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qubprhhs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2omjvyegz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2weegmqlo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfrifyj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yffrhbut.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfoxgbs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwoxyvk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzyrqun.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaxfpos.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lezpquyw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2usxidmed.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjjyatz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paifpreo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iriltpwp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzecigrb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uewqzfnj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaqlyzi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agoorokm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2onjqxvfp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2elrpcgiq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjuprvf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brdgzpql.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcihizl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slvwdnnu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2appfxhms.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvomsbu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mswkgygw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bskcltll.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lifbuokl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiezttvk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkdrrry.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbjetkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqprhni.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiparrv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxdcjda.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2acsqqrll.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xazhwbyk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdbsefo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dplhlkgs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyiirgr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kthdqziu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtjmvhu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnpjbjr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2stasbimp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2amozbfso.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkuedoa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2srykiqhn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnzjrfc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esayftty.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xotowtll.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoqdskt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fnigcnej.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdinyho.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhngdlh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2spvemngx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwukyhx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdffprd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pldjyuvx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epuwvxse.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwsctyg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhidybm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxotuzci.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqglreq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sveiztae.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2whvgoauv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mhamvzbk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tkplieto.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwjivnz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rxswhlmc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxozng.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vwozwwpd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcsaevf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mssizwzx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qehxcvpr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsubioax.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtuprkt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtjlamc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsgrycc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nshrzsmc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wffeteoh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaotoixf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkfzcil.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbvzvah.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbltvfd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfdvwoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqccwzqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkvsqty.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcgebvj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxrvqq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkodzty.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbjuwcp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xckjhxfy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2edbuwhoc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzvpvwx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvjaein.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnmyeqy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fsezsprr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyekzjnv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtzbcdw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwxuqgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmlmhcx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbkhkhd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgnasmu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojipzwll.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfthhfsu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbbobf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpvnxwt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkeqgjp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqemqzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbdrmfl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmyevuq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bkotudfp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qclsdwao.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2axcbbegv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwktknz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2alishzkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvruoleh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xldjzrqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2prikczpz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzumwdy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2svttjswa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcpeexa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpychuk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tginphdz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzqjabm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nuazabzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqztgrko.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sepbvqim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbexnho.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyjdiug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrveicn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkpbfum.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzzrvlu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoqlgfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmhqvjl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2msoysmav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wulfsfat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbfsxct.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odkjbitg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdqjrvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlgeikq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otappmsz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkliglra.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmipzhwz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoyvfka.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzjdmrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mujskrfr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ofohxoqw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqskuzhq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyzlvhl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfynvfnc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmojjed.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvgqnic.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzylmoij.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsalcafa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxxppnv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bttnhjjg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjlpli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkijfbyp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okpblaqk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gumwzoxg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akgrblxy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpozfjjo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhedbhh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzzwgdf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyoixwy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wphbirvv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzgpwxk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgykhcqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlmzylv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igteujmh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2agdkczra.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qavunvgc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgejojo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zbguluci.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ceibudwg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zumstbmh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fabmonyy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pimprujb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhkotra.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kffseqxh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2myngsmow.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpsgjpd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpltsbt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaljybf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2phimrqry.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2btrnblji.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrjzwp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2sinbuxqj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nwihybri.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wytqmoaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwzijbc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eykumcdt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkfaskc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2twmozfdk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nlusclen.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvupixs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzfvhfj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtkmfjz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnoaflm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2azzffmla.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgbgphm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xgieqgja.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdwwbw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2chnuvkju.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rspbshty.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vypjjgjo.html


<!-- 参考信息 -->