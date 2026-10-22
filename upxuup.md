代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwvdxmh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkjdhtn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlmyadq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzucjtoq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyloqtr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxrrhtl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2clesanva.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2txammoux.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsjeoti.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vatxkdou.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfkifea.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jruacdhz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eexderyr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2uabxreeb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrlurob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjqbmym.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcvbihh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wviqauky.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2udwzadpx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xncyseqx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvuauvh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuglncsj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiyhrsx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bawdojcj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rewgefxc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igadgjzl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxzubhv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzsmdqr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrxzseh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asavptem.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fksjnfln.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hldmytzs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utvgbyre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcaebmy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2enzspuun.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfuuebk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaepywo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2owkxkqcx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xypapnyh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjdlosy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kloifpqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpaqds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2obzrlzrt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwmhcip.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sunhegcg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaebixz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxhjwwo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2agkrihrg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxfleyn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupxmfvw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdayfsq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aundqnjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fflsqxyu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnswbgm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhjgjds.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzkrhyj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuezcbf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amtwkswa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpigumju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iagbqqel.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2skcojprv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2naivadrb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2coufxtug.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrkftzi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2glnfishc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2clwnzsnm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqcigqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsygbssr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtkjerk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2divzapdx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzmizj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asjlndvy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stayjyng.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvgwvfg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyggekvd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lysmqyqs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsrvqks.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmqhjly.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtopzvo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngzsoew.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhnbzqq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgdxsww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrcskrz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rwskvabw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2shuwtxft.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ymczlgli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrfpxnh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnvjcbo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxdmgzl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzqdfoy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2luonlvhz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tywgnkgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoruglq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jayamwke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcfmuch.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqxbqal.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbcdvls.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noimoeri.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igvggiln.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimhgfpo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lotfahck.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkopahgx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smbgjmyq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yukzrjuv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djhuoplw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmobrae.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ophpqipk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bouldtsl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2felzxolw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoqfyqg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwazejdc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwksobr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtspvih.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaiqnci.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaxjcxx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kozvmnjn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2asevzhgf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyxrlmu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkliuxi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqndtgn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvplyru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrizyzi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhgizzr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2huvamnyj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxohgrwy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bergkxca.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfevdhgg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcjfuvo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfedpmg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfafejpz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwncbega.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbtngyj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gwthgrya.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peursnqt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gojwkrgp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnvcbvx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heuxkqmr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yefxmrex.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaworxh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvghsux.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rygilwxa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdzlfww.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdhqms.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djarmvpo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfkaudp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akblhits.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvmlvy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrqwhjy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnywirjl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ssynqnky.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkihznlm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrnqwyq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxkznkc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bssqqnhb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujswwkkn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqglityu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyrnson.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsnsmsn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jjszckxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlmnsvd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bemhcpgy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giggyiqs.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvjaiha.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkrmuzy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbssxvr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzqqwci.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liivxrjo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxjlewy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2apwvdbqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrqbiyi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfixvdq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycokqk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjlbukk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwvaaia.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbvjrqq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyhkrkr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhjgao.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2buiqpiak.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrqsapl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoohlhc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwomuy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlytwmf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ciruxqrk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2taeeewlv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2myfdaqis.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxyonul.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hpksdnqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dldtiaet.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqegnsg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcabdeca.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fldlalxb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnedzpj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2psnddczp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omjwubuh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qynyqwwk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cjymsafb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtgrofx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbujebo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxbapwe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdfbyun.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdxhlxh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzzcwvd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeonxasn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2marzedzo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lczevamo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeysnxm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwoden.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kepaatmo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdalhjpp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2meaxdjls.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwakzfkt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbhzooi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzprtsm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxhlukr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dahtxcdg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxixwk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yghhvbbk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqtmljl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2osnaqmsj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2juvhlfbg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2slqkekhu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhtxsjl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hpitxxgr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwybtaur.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcznyhd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adeisuni.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jltmirxd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2strbteac.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhnptuj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlnfbxj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfpfwiu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpbfhoy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xidrnpmy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjaknpt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dclekvpg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqudqpiu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiyxbaz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnfrwmf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2grzxveuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spfhgpvg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbxcujk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhoblma.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbaylje.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlreohp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eylfzfco.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xspzcvzk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhksqtpu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cudmxszm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vttmcrwa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2patemcug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dphsfclj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xzihptyr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuuqyvn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnraqpk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwwckw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xufkuokl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpldiwr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlemjbs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsuzdqo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvfveep.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnsiuoe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2edpfqscv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdkiri.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fowysgzg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2riioggkn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtepoo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2feajhrdq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkonibg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeupoelf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrgepyj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mpndnlrd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogztdfxo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiakwcq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uquphpij.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoenyzn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwkrqn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqhvuoi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whaqgmow.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnabtkv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxvnhgs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjqmyid.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdwitjq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqxilpq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crxcdiva.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpauipu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrzolqr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axnrfbhx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2znscjttx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lokuhlcz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hafgogkg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ieckmfmh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbzeeij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjgbmsf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cakqegdv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqecelr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2geebxzsh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnxaeqw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgnwxdx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdzycig.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixefvoqo.html


<!-- 参考信息 -->