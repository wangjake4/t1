代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hckxpduf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrpsbcq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bglalfjs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjiqrhz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2siiqzvdx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qktfqfhz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zklqsura.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yifyrlmx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otiablnf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2akrokvxj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2urmwvizd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lypfygvl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oursbsuj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pffyjgrz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyhzath.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whbummjb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sslrqahg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbozmsyj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcuqgyx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmqwqjj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqshucuy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxktjuog.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrrczyk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clhlxgnb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhmnnnl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgutndgn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwyqzxs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqeempk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqrgbxl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yztwywbl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2txjcedrv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsihjio.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kamtjbpw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjokemj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjgcrrq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqzeycf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjbxom.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsiyflg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2biagtnzo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2udabljzk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxyeaan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxlhdkz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvtlssx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcaaphf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpyhbqf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqhsyzp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxoszfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zscmtcnk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ryttimnh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdosxdh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jooemeec.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmriqpqh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2osznhtjh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzjfchf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atoctddo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2admaqszm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epidfcfg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqpcisi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbphnhm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blttcarg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjfrmey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwozhcdn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoiyton.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fakbbehq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcavzpdh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuryfoob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lexycjek.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvayalqh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwffcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwlgkfz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxnkmqt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2exrpomta.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2inkeerpd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lteevyds.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2evsxtvry.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzbscoj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpvhcgl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2axgaxmeo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xohabihu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2irtztpuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hanufxja.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mafswfyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bveyqvpp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wfefkrrq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnvmzgx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbicmhjl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcpsta.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxnsaqd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnreeopp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2isxyfroh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2deybnqaz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgeutp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efdyafqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fasohczv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoiijbl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bidvtrha.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smdqgfdo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjwdaaj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2skznakvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynetnngf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaawazn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hscxtbhw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoeugse.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyibpbb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cggxtcho.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2prpasjjg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhcnlli.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qoodcges.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzntkxu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksglkvmp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfayxes.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bsufvtqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wccahnla.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehinvayg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouafaseo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyewing.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkgeosd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwydoxic.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpobksua.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xkidotdr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dakfvgrt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhzqvvk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnudykwr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwektosr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btyxyjao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bejwgxqi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbhtehv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvtnmlj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzamftea.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2avvohnxi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdrusyi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvcrwns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcqvpaj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhsgcva.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bhflmpjm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzrlcml.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kztfnnlx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hljdeetg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjjghbx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2daanehoq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbutyepj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgepapw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyhashi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfpbkib.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2anaqhfyn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjthcpu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2clxyrsyu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hftbefto.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyxkaug.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shvlleqx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bubdrkkk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcmsafv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzycpdb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbvedjb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meykwstk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwinnsxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2isiekumr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrbtgse.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2apcrehmo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwabzsu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzhumjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pygecvbl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxuptl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxqytps.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeuusnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbripec.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiwvlna.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vcniwwny.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xnohplyj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2asslcxla.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2svtgqzpx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkwvxle.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlsqwih.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrnskrz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjhvpue.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aermtzla.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktaxbu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwglekpq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrvcecw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhepgbni.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2umrwnqtg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxjgnf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakkpur.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzvgvmk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plicfbms.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnktnzc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xllewtzk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqgczvp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmshusi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xahutwyo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkyeaiy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgggknao.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcjvnmh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yukgytjj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbrcqfz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jieclxez.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fyusicam.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpdobav.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tersyali.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2musoinqp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zikmxind.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2neawboju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dvetmshz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfoloxj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfjltlp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrucfc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtacgub.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrjrwhc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsayzay.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzxygjd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsskaia.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwxczin.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qghyaprw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwtazxi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2barrenyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngsaydc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdfmaqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2myddrpkn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vjceqabh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fzabxwqg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2heshksuv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szvbbbzr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcupljhh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrdyuqh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2geshbyek.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasnmuh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbwzqtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwmwnxl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjpxzjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eabwusqo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2htatuipg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgwhbvr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvjallp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorlbgbd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwglhrls.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvtkyvj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpsqvbt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2imunxiod.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumtnrl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhcqtis.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2usriqive.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgqipka.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epoxblwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egojvlbd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2antzachv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mriarxnm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htvsaemf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqshmfic.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kutoanbh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2srqohlaa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxmupgr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwevggv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbaqzpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2caanmjgh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjecxywl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2usjbjvay.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tngxyesu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqzchyb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcumkqx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyljsaw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iutflbxm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kopnabtw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceibioal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlhsxkt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgikrj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkihffc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olcczpkc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2okfyrtjv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntescnbe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sloubwcd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2youtivmd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zchuvnwq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2soelfepi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvexxp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxxejsu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2skiduwtg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2irxsfbeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvylaz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvrnpct.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvzhdhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2awonmqxn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oekpkdfx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxmwbca.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2obryfwoa.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdnkpzf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqfytrv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcdrpac.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxmaru.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzhpxbn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2udhqxhij.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjljyuhl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btawuwbb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yroykmqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zmombcsz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wokzumjz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfuwhsr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrsbegk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmsoifj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwycamvn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2osnlzruz.html


<!-- 参考信息 -->