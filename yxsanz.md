代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezspnpdu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxudixwy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfraep.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaderhcq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmfsrao.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cleyudlp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfogmcui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqizmode.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fxznhsit.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jplcafxz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2azshuayw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxwyflj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgeuak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjqvepu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuhslwp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxklxsc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2puwcupvh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emtcmmmb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pehagymr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2obqyklrd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upkojblg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrrvmve.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2urxcetzb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpugvrm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqvfocm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfijoxdx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxadzudc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkoshbc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aozcwmki.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2juahqfqw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsewdhi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2foatqxqa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwwahsu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlpepfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfbabs.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgsuuup.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnbbucc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkmgmdl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2howdfenv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoihmjol.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcoikyr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvorzjh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgiwadz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2temovvgx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbenqfj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qttcsfkj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgjhsw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwbbutr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2axkkhckn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoktekf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmffilw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hikjhocf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlthhjtb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvawgsfa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpmrgic.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxpzgsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cywjotlz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqhcadr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2stlleknh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeaurwe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvocleq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2naukopbb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhhyzms.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2soxihtjy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgckgbdi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzqznjz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hepwxghe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbkhmcu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lstqsmfp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcrltjq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzskopb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxidsmz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvumsxeg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdrbfil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoqhbsz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrigtga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlbpkyd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rclixajp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xilydzlp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jodzcrwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rycynhei.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtgcjql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsamcmeg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2sswvvaau.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrpuleb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfkuidq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtaysmc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdihbhd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gudcciwl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrbwkpi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nypyymae.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oksnwfjj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tocahvnp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlzozso.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqrotiw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrggetm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmdqjuw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grihewum.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxoigkz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cufnfdsn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxvxpja.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uynqhjlj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtonsfo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdudhcg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahirzawc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgkwhay.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdesdss.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvvhaun.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoicuqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fadlgjrr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcltwnv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2scpglnal.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbccrkfb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaplljbq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwajatq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrktikcx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvefnavz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fswhglvy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrltcvd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqezpbr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2prilibgc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoodhvp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnpjnjc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyndnorh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwzyckn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqtpayt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkkpvy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwosqbs.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jduplvew.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqagfdlr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vttjhrja.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuqbver.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxcute.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glixenau.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zwynbkpd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pptztohq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoisfey.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2djvkmkce.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxlovsw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlduqauw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwjmnph.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2difhuvjb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2umuxxhwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqueguvf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jtomptma.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uljpavml.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rexwtyxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlrmpfh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhekabzy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulezkfsa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aefwqten.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taqeltvf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjnfbek.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnnxntj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teljpgla.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczboin.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jhinsgqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdohpolo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbtisqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkesnsz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuecswm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmmkfsy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpklyodb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grsynpxc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzlcurx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2njbkipwo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzpvkno.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkbgddw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjeffvh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2licoevgq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwsxkyi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2npzusqng.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2glprbdst.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uinhdbhy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpqvtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpdsdld.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgzkwgj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwydwxv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rotnrnim.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2utcpsymp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgshrdk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdlhuxk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eywyorfj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnitirh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeeztek.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krqkjady.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybejzeuo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mibpaaae.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbxtwua.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdmswnr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgtpfiv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfnjavh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqfyyti.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wznsnzfz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2agpkpyfg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xetgngua.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxijegf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nffgbnwq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwsjsq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoneejy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zqesoezo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfusjdm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aozldfvl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzvigcl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaiqjzn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhwxgvn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwufkhpl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvcveji.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uafeoxtu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlvcpie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zoczxeyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xybwzlxi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwtggyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuhpzru.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrzijvn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsmkbwt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwamxnf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyeoidg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqutiwb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkegut.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaobfrd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmludrbz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etgrwpkk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnmwewk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dveycwbm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhfwyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlqugoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrllouj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nghedisb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exjizjou.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhdqveq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulybtyf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yojcpcye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npasntie.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxksmvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umkrgpbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcaelvz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aubcmeda.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxihqvj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ydacutng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayowtmgn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswgqkk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnqjnzd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjieazjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlpfwti.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzizitph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgokakx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbxwfg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmqebxa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxvjmbu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoddqgt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxsozln.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsffvna.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2locyuxgu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshrmxfp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2llrpings.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvunygo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdosikce.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hctxpodh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbsevms.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caqunxcs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djojvwmn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcuwchj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2milszblz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fryugkpr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uffbuktf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwldebcg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2utucsehk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atnxnftp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mobuwgdv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfjsqd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avoxvpqr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsjrlsn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwqkcsk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxjbhlj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhlhsup.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaudwbd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkmelms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuzmvml.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nqosfvkl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2homdjnyh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjdqcba.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwagqrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaxxsru.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qftrxxal.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsndqhf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2etctfpcq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmftiapq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsjkcrk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvcjul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmwkwbe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tajikcnl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqrfidg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aauyvuea.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rncgzvsz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyhncdt.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyvduzp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimmngo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzinkery.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqinunib.html


<!-- 参考信息 -->