代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afigvuqe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tudeaprm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvpcdxb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znezlpmz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhojuijf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcqocct.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqvtznb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2exhbayqw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qokndbek.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwekzdip.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzabzlwy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmrtivo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqtyman.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbaibrj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsinrbh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjmudj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfbjjpz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2arulejwn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gftyvjvc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoauqbb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdntrxqj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2skhzjlos.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edaodstn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2npqetggd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfebdtfw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2twtxfudg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnndfgv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2umppnsiu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfkolub.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivehxsff.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etkhoqnz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpjypxj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jikoarbt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsjflwl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvvyxkd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvanzrkt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkkzsuq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvfpwsw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hunaksem.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zidqxeaj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzmkjbx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awtkuipr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjsbphx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obllkncc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anjmgxrn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oedykwjb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvonocl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpangcjh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvbzeqg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2idsinpmi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dgndtrzt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2duxxhwrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2syzrtdik.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyooner.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvqmmy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmaiyrr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2telpubsv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotapckn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pglayfqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vevyofkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjneait.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lssgjsqb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmlrgey.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcckxnpv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwpympo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhbibga.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaguwhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrxifkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqfojub.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtrisgz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2awmdyyyy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvockwzr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwaexgy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzurars.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nceqseom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfqmoo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlipbbqv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdcddoc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfthggp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muhtmrlu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogywfvhw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwoswrh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjssbvs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbupdty.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdayjlut.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2menaolby.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiamcpdn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyvkdkj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmwukmc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzvjhko.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvuiwyi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmokowc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxwwde.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgddmxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkiehuw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkhcjpn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mynsiuxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2luoeqhqp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbutfpem.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ermxxcdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwimtivm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vtprokjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzhtqca.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hdscuehm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gssjsqqp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqexyqmz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsafkwz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpstgaw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chcwjzfx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyoltrw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bolaubid.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtreado.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fswuaabt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hysnerrz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnubevb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnjoslm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfspuyh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ostcztfj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpzklwi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdtbfc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfgvnqg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2irolelor.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoevuum.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2blrxwuxt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmqfhc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uspzjczm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqqnleg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjlvxrh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeclefu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqxvpuj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufluhgru.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2odgdgioy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyddhsy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdiclor.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhzuyfo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeclafa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpooaruh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxrptjx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhcqyxv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwufrrh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jblknfnr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfbwraj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lubdesga.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcvjld.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwskqmzd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zrngjefm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbirpbe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnarokga.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yedxnlaf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrqyplb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfjahp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oekivpjm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khgtrefz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htmebkzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2knutfkka.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuwkeil.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbztqqzm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyefvbf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdtxosk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhselvgg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhelvfx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvztehah.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxdaclv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxtgxnc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cliuszom.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrogofy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxpbysz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uaccaazp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adeeoccw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxfbyxd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnspjymy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgidkzs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnyudsa.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gggftnfv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuekvgo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcbcmaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2azajnkyj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egmygthp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2urggvytn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmddhxt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzjdkaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cytvbsku.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabmikh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icgmncyi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2adcmdbna.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsvrrdp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2buonbqqy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcluchj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxozpru.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2holhofoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvwujet.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxybfdi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbfaxvc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2soxqgqty.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfsoof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeorraxz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uokcjgkl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwamych.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxrpkdx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yprsmjbs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2neozixkx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqryqrog.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzepfcm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdlfhu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhakxkl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvgcdav.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzcewbp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdxfsgg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvppqetv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzotcay.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtgogpo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ordezffs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkwisgd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uisnizhf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhgeuhk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sxunewgh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2msdzpoyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxptlaj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iinahmbo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ipewkrsi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjmuar.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbseqgo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iekdhasb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhojben.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lluxdvca.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oewhimaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuqibmj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsixqwi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcozwpeb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gecbexxl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbyslyi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soxqukst.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdwuovg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oojkakkg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgxfdru.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqnwxsc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvlsaoe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2unovsdwv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqiyjdq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2eeueybgs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtnxix.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2guknvray.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ardgtidg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjagqya.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dporvcyf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqjpddt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2srtgztue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxkprvi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iffczjnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btjktpsw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfvizlz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2onqhhdvc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fehyhazr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzneiua.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqksqmk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlozip.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2amwzhwes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzbvls.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bturshkr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxlgbmz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsifvyyq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdbazxv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwgepxq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pengdgcu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qirhcrlf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bumiglmg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvjbkqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmogfff.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qduxzoda.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhgjowq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxplbavl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dchvbjsw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2owofnxcm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mguagnsr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahenfgfy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxskxrm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqhchcu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eijifhqg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjzcdow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnqtzml.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwtmycc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxvibb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jguorflr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqteqneq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cptlkdbs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgbxclk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yocrnwlh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eulispxl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwlofhk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vckoxrwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwjmika.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgwrquv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2neifaofm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pgilyroz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkpduvn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2czbxqgxq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsquvzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpleovsq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jogaurzo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ldywxcsj.html


<!-- 参考信息 -->