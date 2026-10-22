代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jybsdduu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhytfyf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xilmnkvr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2urlaukam.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dedlumhl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2scmbxcnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbwndly.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbebwh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2puiibktz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyfxpdw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2anzglukj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2darmndje.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fraqukmc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2astgrnsq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pptqhxvo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnycimhv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikfsgb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyjncfo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhuqmuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2idbbxzsq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtebdbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfnpdkw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2trbugfrk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymeurs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkbeyme.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvchdrtq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfomlif.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qawqaxim.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svonmstk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzhhudn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbauegd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgsrey.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xerqrmka.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyklydaf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iltinklc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zseuljak.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swwkzdjp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eafwqzim.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2shtzzdru.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhprmusx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwpfrof.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbardna.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oylcdoyk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvknmquc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvbjtus.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrzobfd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qozzrbic.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dldvzlsr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwjkieb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shnqslxi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhivpjo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbyzujf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwckgtd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cizqngeh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpbywgi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2caqicwte.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zykmpzjc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kncwwtaj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnwqgay.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcbqsip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdbbqfn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvozzuw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbsvefn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojigushc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhgdtp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnqehky.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgolabe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxtbhbs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwlgyue.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcfiazz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxzpsdu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzhihfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjgayha.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvlutwk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqpupd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wasaqbei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxavmyxl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgcllcz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzsvyzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzlhles.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2khhpfvjj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzqigkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcbqsxa.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oubfcopj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrvirih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdrhqmy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zmttpedo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2upwtjjfd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fquttije.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wxktckuo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmypzts.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dkupfzra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psvdzmsn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fiympebx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdlcvja.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfafycy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mghiatny.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guzrvrvm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyubtyqh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akrxoydo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlxtobv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiobfpex.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qynppwqe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgyawfw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuxkkph.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmictww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoeayfp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swplwrmp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmacghp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcggkipo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlilewh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2necckvoi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flntxpda.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwhcsps.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2geybzbos.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aawcjsui.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnbrbek.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnkrsvb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2znfdkqbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjppjyw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnwpopx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhczfpq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzzviyk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrapgls.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlyfcza.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqrckio.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzuqapj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qobohhqu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avabokcb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudtmwp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjeyntr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ieejeovt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmoyjnq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbhaxtd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbahckay.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grnmoeuy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdjhfzp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2milegqpv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgusehxe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goehvblc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuncatk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2evzatmze.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmwywbe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gipsfira.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyyncfb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtyokxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtfoykx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnkjzqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjsnamu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2liacxsjl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2osusnzkx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2asscdudi.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkfhwsh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2spqytvsk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbnvoob.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bivdwrnz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dkehbxjd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzedsyqg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eoenwgcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2feenvrrr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzykquiq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axdauxnh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhtiahm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esmtfvpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdsbnqb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkltimaj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfkutqt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rodfadfk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zgggeznf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kftyhnae.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpiahkf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvvlufe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapypzdj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrcklax.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pofzlgfe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggevfvfo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hszovjra.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjwlto.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cvssjlky.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgyvvnq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2blxwctbx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2emmgmmoz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvxwanj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jvefdhzd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfyncco.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoodwow.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhqqnaw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlenhkfi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxujchn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2relxasjj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gumeftlf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aevlpcai.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrdcjso.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdhewdq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbawpdh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2epmypjrh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kohwvaku.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luweouyg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qumjrlhd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2picjfwwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtswdfhx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvublipr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmheyzog.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npdwsmjt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhbpeza.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cognxzkk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvrcwcv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2obkummbb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zaywqixp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2neeeosro.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxdfso.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2btdzevyj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjptwao.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2abaqxesr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2luaanfpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fggycfwy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrijhreh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxxpsbd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbhamnn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tmynlmbu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiaghly.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zsygqdbv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrkaddo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thmhlhvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bavexwrn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixwtpyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gragifen.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2skzhfukr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbryth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cefjzrni.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gtacthpc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xijvjuod.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2smvkyjnf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqrwlln.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvmtoha.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2srwdpzlw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2urnrmlyz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lellytif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkcvzus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srjfqimn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkzhfqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pghucrdm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2isrlyrwo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sydhjqvm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hikwdurq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krdfgmaj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zixgxepp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msavajzx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzxuihj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoghcmx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjryzzn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxcwcfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtthjlqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcdjsqd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjjgth.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdtvsmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eerzxemx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlauhazb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxkxsyv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivaxwhm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiphptv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wveazwhu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwxaydu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2olzobdtr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzhkxbh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrjgedu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfhxweh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2glmkvulq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uluxwwyz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2auctdfiy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ennzreqn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvttzqk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpqcamm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfktzizj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzsxgru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gquumgqw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwjgshr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsrepzx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlgvfum.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxctgln.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmumbcjt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkqovpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2daupqhvd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrwhbyq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cptkydvz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbpoezy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruemgitg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2whsdfefp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfldnuf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdylnvm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnfkllg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2utbwljqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmakarkz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlbulr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2moutaqgs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zczgfszr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sprldmwt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcedghbj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlontpu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzioczda.html


<!-- 参考信息 -->