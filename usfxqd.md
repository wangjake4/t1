代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvuunhu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaqwnmt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhexvax.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vudwnquy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aldkzkbc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqdpfpl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigdrmvl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwfczhx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfejgvx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvybwhfh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnktuhlr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxqemuu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdclasgd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emzvffen.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwmiqzg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdxghmt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedmmol.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caxmohnj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wirlfnmc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbxyuuy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwphigm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejudmmra.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2suartkax.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kumxsmzp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaetewkd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2glkvxhiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2eddcosaa.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxmwroa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trblryle.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbafwxn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xynynvcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcuqzbh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtdblbb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkspske.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruttompm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaywqxhs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pvehgvwo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzeusi.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvbfxeb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxquddf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2snjdocyr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2meriicqy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfzzfkj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnfnelu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jepplvsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdflwca.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uczgxodq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgwmeup.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tthybpfy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdwjls.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnhooel.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frqzhfmk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwofcxjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qucpmytf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umpezqan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiutsww.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kedruepr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iearnrgv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbfsbcl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydnlgpi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvappar.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnhrdch.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxemrsd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nffxucuf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2scpmutyz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2poxxwffd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pgospdte.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jokbpkoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsnjgwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhsvvou.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkumyof.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lshnnmuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eedzievj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zumevcbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vowbrqgp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgqqxud.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfvwtlq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbifbpta.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoxcpmt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvorvuo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yygdqwea.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijkyeui.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grpnsqyp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gixjpdpl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlweecg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqrjwcf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfkaurr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqmaqbc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgajses.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnagxjtz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzoqtnk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dumrskcl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunbzxik.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2haiczphn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxafrl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvbdwcm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xecwiven.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxwpgpc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twbbrucr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbjlmj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzihecy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2efigvhxx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvdbiau.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcittgn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgnezck.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfocduhj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abmeagsu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjwpoan.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqsomlp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhwovef.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mivtzohm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdaxoxt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrjwwpv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjawzf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdjxvvx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvzyimw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wovjhekt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hskcnoed.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjctwyba.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqoxhqg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiyygca.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlydtgmn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqglnue.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmqmlsl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrvwucp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrzyonh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjrfkoo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vixzijdd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoqvage.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ooctpllt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvraishv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jthlrbjw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdwcoss.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwrtpa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwezbqys.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcqtpmo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2znppuflu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaiaxzl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uyetoliy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2plkekfsz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brhnjmes.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okbgtahg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwmpqcs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drwnguek.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znbhhbru.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueijzayi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgmritw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmttjma.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgqudq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgjztal.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iccnxmbv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzglmzmt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxqpywl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2teosgzju.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvwwnbo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwftveo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2shnifnzm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrcuiyj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yorlnoxa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rezrxitm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2txupbuok.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcivke.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxkisio.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcmqem.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtkwzay.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tztvabjl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bzitgelo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suqvmkir.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjfqltw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fialurfy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekmemjp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2apcvbelm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sltacyon.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnknfnop.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhplsgo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2enuyrhpt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicpyrsj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfclxqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgprvdad.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirgqrfr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjxduul.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2asxcrlij.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymlarpa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfpmvmt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzbotit.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdsisrw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2updyuuda.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkswqfi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvzmwlv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ibspwpmg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xazgkllj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoirfxy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qejkipmx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pigfczfc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnbjdkd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xstxhbql.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2iplltwxy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkxdota.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutlxmwi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zreaegtv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcgrykr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jddmonpr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmybgod.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqaddac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gdufkjxy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwvzdu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdlzmgo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rairaaep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeljufl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemhszra.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prgxqilo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukhktt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnhnsyq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxsqlzg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcnoxuk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2btetvrji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxgefen.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkwwxhw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvvvfri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohirmvbb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2igsxbxau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urthopvi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2utqlevkx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqlodtl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmksryu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2futxxcts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwrzsv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgltzito.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvxljip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrncsyu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgtoxso.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnlfgnw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2njlhdfmv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugukahea.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfreonvs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cepkvsho.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywotlmgx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxqdnkq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbdlxpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvevtpm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcacpfq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2slzekjys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwykuaq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtapgsm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyusydi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2asxviacl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2iognlbxg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiviccit.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2osgoxvcy.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqvuasa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpqriey.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aglhtzox.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqezgpp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzcoasq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqncumhk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvopzgdc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhuvjek.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wshehiuk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjxyskq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhinrqs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjbzwvb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zubfjmtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eswgfdqw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjshdsj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmihrxu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlxmvey.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjapuxv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgohjvo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nomqlzxt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmbhnm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2avzwzwst.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oysvidak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlgtlcl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupfxgud.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnlazdg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwldakk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpyrjle.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tosdhxzo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxflxsqr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqcbio.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdndnnej.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2etunplhj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2reszcgom.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwxkyjh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltljweat.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vunaujmu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qefrussl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmcaxsp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jfthmszh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnojqcn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiicciuf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdemfno.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaxcypz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kugvbzon.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2icsqlugo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qykgtcin.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpnnvts.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2eueftvye.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzvkvef.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjxdvaw.html


<!-- 参考信息 -->