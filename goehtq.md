代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmbddki.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceonbmhj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lukqivhq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axvocxgj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmidqkm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiljoblw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqcqyuq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakxsogt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxusoktk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjncdplv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjuojje.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxmospj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrkrzzl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmchqdgn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtbmryr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqokpru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzhsicy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwlhwsu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2waagqpzg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwhootr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmrwazu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2blbfvkuj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbchisgp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2axgucres.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglsbaui.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrtyiiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2plwqlvnh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmaasbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuhaamb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2neratbyk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipduecsr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stpuaerw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoicivjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzdyjc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlufjonl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgyxwvj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhykirt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwddwjmw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfvpekg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqatqxtz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyuzyde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkvbeef.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zprndlur.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhkuyye.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhucmzi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvrpwil.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoadfpis.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vscwkxgj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2onaegyga.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vsucctpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdxgphg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2poxbgrbq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtpfqfn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpbmvjv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfhurlq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qluztsvc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ereitqyi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzmtxlh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2femwfpyl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcxisuv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdvrxtf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvbrwed.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2weabiumd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylcbsyu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hstdruqf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvajdtzb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuneppc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bpffayeh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2somakanw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtupbdsf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcysvaum.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkfrlb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2njzwblbe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2peqijrhb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfcefsa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnyeuyq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueklkpoy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhnhia.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uifcngwm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdsfprz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlbkwzi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjzpgih.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilplcckw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnjzqmt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoaimmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zszcyjbh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urjzbqqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxplnik.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2odnqwpav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbprtgd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyuyjuf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2izfjltni.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eijjxglv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xujnaovx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrpxwp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2masruhty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmoaisr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvhupqs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsqtfip.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpdewrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzdegsr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mphvkalb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvukgat.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vviowqzl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpxlxzp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdfosnb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rniiunov.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkwyqtw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paxbbjnw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwzlhzg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnhbcyr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdaiokb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2roxelkcx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xcetkoyj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fendkgeo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqufqmjv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfpkfwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgcpwlb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzuffsb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtvenhx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfqvzqf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hozpnksz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2znehnwil.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiropgjp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2helzuxhv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qabhbfrz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabgncui.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxzbcdj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aovwiqhw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycfzxj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2drjsfocm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwshyhu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjzgkaj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xupmfrdz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2objiwdgp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbhxmrh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwzuizy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbxbpaj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyxrkro.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyccask.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xarhjoho.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyugfon.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzghqe.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anmbrwnl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyndapch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2avdfolna.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2metfprgv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lajxqqqd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnzqlur.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2amxexsun.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibumaigg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshzwzdi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjkfgbk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdznwzmo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyykvnh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuravpdl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxchycp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbyvwno.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eshcdwik.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wavgqszl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwaafcx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yynixedf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcostg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbbystu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qahbvpku.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pktuhzhy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vmowgeoy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpsuyh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaemcqth.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gixtyxci.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2valmuwqd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pghzcupy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwoywuq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhryohp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdferxqd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkizohg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvraoae.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enpnnmbi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2knlfrguc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaywrts.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalmcgej.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiizswf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chyvwkls.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liaxxyuz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvlbmlj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2blryjztc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuvwjdw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaqzxge.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wldcdxjc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqbnfzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbvxyco.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yvawijay.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxtvck.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2paqyzivf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2foogxlvb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxejgo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hisuipnd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toxulvyw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjxymhe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyekxbyr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiwzirn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlbbufd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbhzcxr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fndujsqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwohdxmu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnksdoii.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnedtmye.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvgjnkg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqmwwbf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhvglvb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfkgjul.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cstriyhk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvllimi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2srlvefkk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgwuhh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpruhms.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpldydq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgvrhkb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2abaedgsv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkewnxil.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zthbchhu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcerbdm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmuxalo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfgcydp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmllzhvq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqoaypf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbppxska.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fdajdjvt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqcycpd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smzafbbu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2njzlmqex.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqsxnye.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2audnseqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifooodll.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bynwoiyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2guebbvxg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyxqina.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aevqfmyr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mamxojry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2udpbijqg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvicyzr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkhiou.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zttgoytp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2irozdepw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnbfgss.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhrhczm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2inswgawk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afoukmnn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lcljzdff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rccceusf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xynhcxya.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyffeprm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tedrlucp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiobjijp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eersmurs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwqddby.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtgwln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obamdkwg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaokmexb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dojsqqmu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyhdkhp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2reutpzoz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrfgukd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwiabww.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvajfafl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2aslozibm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhlmyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcztpos.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tytayvrd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjhldmk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxtnfsr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdbinqe.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfxxzoz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhtgudc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqrcfkb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kntbllza.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcyvogh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxhlaf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxahgck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fafxcyey.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nowqgasp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrsckxk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsdiigr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmjndpi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmgciqt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saaavnbv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqevnjg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2oftcxadc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgvntse.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsargcmk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpafizpp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nijlifbk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbufifu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yksgelbl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omhsbkdp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tmykitaq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2adbiblbg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bikdrdoz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oesibbxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdcbcf.html


<!-- 参考信息 -->