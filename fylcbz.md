代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpcdeht.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pinenjtt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2njsftzgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knlnhopk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxylmglp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoadkup.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwkkpsf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbhujp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2klsvzpkt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnssmjfc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvghbz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ounxhvke.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkspajo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewakqkfv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzgtjcf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtezcyl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxicxe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaaowhn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwcwzpl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtpgtcq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfeiqya.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkhhplv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaluiqr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2onmblyyv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtcomij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2azshkprb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2codeybsh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhsjxs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrtbnwa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqfhtyy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2reqrbseg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrgvxbj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edsgzaym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvfieyl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrblfdye.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxlwxnm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rucbapfr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoiyvjd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vammhdfq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmutmly.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dobbqagp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coxtrlan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2znrbsfyr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjkkou.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyrklet.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmacijl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgklnot.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsrtpdc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwffvdwe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kxczmqdu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oycirtfk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eumkqotp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2obfqzpuw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwpsgyl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvixvrj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmgmkol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvayri.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethbcjzw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aguphjna.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhixaqfm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrstbcg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzftyca.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rflqspfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gecrhzwe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwcdhid.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkzjgaa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlouhpvb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmchseq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2laynawyr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmwcbbo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tftknuhu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmqeoka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jobxxttu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxrmcdg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqsyueq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjghixhr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtpfkzx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyywvcxz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2eilzswle.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmfprnt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhtjdxe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctyyqib.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrecgizn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarvdik.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzjagud.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdwfiaj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txwatbkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrkopez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2znwictyy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckitdkuc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwqrfut.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwvwyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hixoasar.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wqloluzu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ersnfgro.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ftziujbb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2shsruxta.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iaugxzhr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcstzbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjiumna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcxbpqe.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkhqykc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbxuuvh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2egldumas.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2srwfxwnc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xksroryr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvtrgkv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhndcdei.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjnogup.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdagijv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpqxnjv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpildooq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsdrnbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxbpmnm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jojiulgv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehjfglw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwamwwqo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqtoqfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyevvzb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgibmlte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqmbthh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oyonilwh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvawnyvv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzmdqps.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlczarj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcrblpa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tguphdtz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ilamhffx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgqavxg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdnrzad.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kvugiadk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhfbuoo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvatthj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcekmfv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqbwepz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsjuejl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvrdxos.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkfztyc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrulhrwr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qexkskdz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ersgyarc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dztmlpfq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szvwjqjm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prfcfggi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvlykxm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tpretnps.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhwznzz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juciivku.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdbyrfv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmqenrv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkebxqef.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgahexy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emrgvyes.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqaosa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2njxsekxw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idrhfngb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jplhhiya.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyrmely.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwntmxe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivckybuk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2svtbqbnl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdcamrp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnjveni.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zzousavs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxdhyj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qopwechz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xyldxwnq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vngurgen.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtcrdvo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kexoyrpd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxogmkyw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vogsbdfi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgppptg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2talquzoi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adeignis.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2csolpjui.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmbymuq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yldsauar.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iapwdeui.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycufbgwr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvyssxd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vejthzml.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhhklwi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqrvzep.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqkjqkb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yixcsrvw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxrmznq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lasgpkez.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2axynwqyd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2opdbvjye.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgnvsqv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbwhtyf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzeiqjb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwqnldx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2esoklemw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripwvynq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uncewhvp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadxehsc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpspwdl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vouglvlc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgjykpd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfloluck.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2timpkjyb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcolcly.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tciqvkdx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmzrbbr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chotnedn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyyqzfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgyiyvj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yajszjpf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxumqlw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnwxff.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvwsks.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iazgpdcu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2reqnnoak.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmcwcnp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uhekljmd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2elqebosd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoaohbw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtgminv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iuahupee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2alntnmjq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnuulpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiihzxsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtywecps.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdysnbbb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqbloza.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrhxkzt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjijuzup.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzdfyvl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axzlkyny.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mimwrjbm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2itkpnnxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhsvokt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeqrhmd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjbrwld.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2roxhprvz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezebjogg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qntxjcmc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuaeuqq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyshefkm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaisoadl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2draxrytq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkozdbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjrwtto.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyrgoqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xziklslm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyzjkys.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lykalqrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czawndpg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqzqrml.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2omfnrzdi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buzxxpyy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyyixdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2loaiahnf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhkqefd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrzzdp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cftohcuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omisyvzb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjnosfy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgksswxz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mewlzkoz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdgqffw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzokdhk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfizell.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfagcsq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrzsggg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjumtyn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nudyvwwx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtajmw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vidwkjcy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxicjqrd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuschmyc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnwtdoz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hieizghu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsipqsrb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2smyfpybc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuakllj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fijmeith.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2martaxpz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxlzyuq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utdyrhve.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kedygqbc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirhntqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtzqyrc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chbacgnv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bngbhvow.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbfckh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvsaxft.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ludjilgc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsvmqut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnndhiah.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmhfkr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxwmaak.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xskhqmzk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2dshmgwja.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tupibhoe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqtiuzu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdenkix.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xflxbpxt.html


<!-- 参考信息 -->