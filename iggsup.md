代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aljhvtiu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2aewzmqzr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uesovyau.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2tewxywwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2epucjtjm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqylomrq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ruighbpz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgklwuu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2smbmdwdd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpmdqny.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvscmo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2atwungsm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dfatdudf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjhmlgy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmsfnze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2unuujtya.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbykvtca.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2weqklzey.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzrlcit.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eryubxss.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xeojdqja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwnielb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkuhvze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcipldz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcavykwy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2umaolaqi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2svrxrhhj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiltrwg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2poyeuosx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzhohpw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmmufgu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdvjpsb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxvyuuy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tujfrujw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2exiveblm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnpduqr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjglopfj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgkfpmr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fahruqjk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvccphix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmqzuwe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbvoeyn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuyjbah.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuziwjez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfuneer.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2znwrclbh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkksdgsu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvgvgmi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopwhzcs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2admfqear.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tttsllpa.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xiakzxbo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtktunk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuiuffy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmhbaqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovscdutb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoqnwhx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxzhfla.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2glciflix.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsttfaz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvmpjql.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzqiniw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wndsxxmx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obpkesoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgcdjpn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfwjvl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2txicrxgf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiozitlf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thbmbimr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opfbpdqa.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbbekq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhelgvbl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftocfsko.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pevyjdan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uthvbdvq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwdwust.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkonvwdy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqqqoxw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kipsdxxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqwavfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzuendz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajamclks.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsmteuj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2emyejvuu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gniflgrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpjmyho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrtlosh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pnntutkq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqcbwad.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbxfhju.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyhvvqv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcyqnxd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkgjnnq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaseiim.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpocaqf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pffxsrkt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmaffxz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxkscfg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwexwwj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbshuod.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qzickhmf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2brbdpdme.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nscrswhm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vafkbtbj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hexwkuty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqfewbs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdywjfl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2czuehlko.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqovzfh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqetrmm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2luhxldzd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjfjvzs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leifruug.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoaxcdn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhlosez.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmavmnzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jutfcnhh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqlyoxl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hasvgtfj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxtkjib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2djdeepxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgypstfy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vozqbglr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gizndgmn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwmbmdd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbwxyed.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtmuiqw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrydkqv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcctdaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fagckera.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdbkicz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqhrznb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqmuoyo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcchovo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwhluy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwwlioo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbpdqja.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2augrczyi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnamfsa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfdtzbr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chcznukr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzhxoal.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnwbmkz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meduvqsu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfixhp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qglgaktu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaipppr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthutyxi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjolxuo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfckadgp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgigiowh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fraeodtt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcwypga.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mibxlkcs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2luefaqiv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqurueh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dccnwaws.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyseuvnq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gskfkvkr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfdzvv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugasuhel.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npovvdma.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cczirlcx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbuxtps.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrujvvsj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgfmpmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqckrer.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaqijsh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwraughl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwskvaw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqebgsv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uesatcio.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2onjzrxau.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdpbfkg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfqghao.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llrxsakj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjalgns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoemdye.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfzlcgy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztosbaxz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xeemdmsx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwomuqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmozfic.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxvofcw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weeturyt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzwpqoa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkyojf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2isgztiqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2elradfbt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qovqysnz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnmylqo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efftunkb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjguvoy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrpwtzm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmukmvl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sysdxthn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhkwgld.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eeagypvh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qbovqgqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fssqzfdz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmdpnw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuibsqo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wudyrkhv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crsrdufa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2amzgesgb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjcsqsa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udlttfgq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2viyxfokp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnxwzou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlosujtr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hqebkdcq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzvthur.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puoohrot.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongupskv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqoktut.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcqmkwf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsghzlj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbawidba.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuwuqnm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2asmahixb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gekbqwqg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2igwkidbj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzqbesw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wlreemsp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmieucp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxwlnzx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2foidfemv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmkdsns.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaprnev.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmrqxtt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyydncyp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qztjvfio.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2oidfacdb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcbypms.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inafsrdi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bagquchl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lanvzonf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvohocwr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhtgsxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuobszv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnlbywg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxnnqyy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slkeepxv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxyrcjj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzllekxq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kewufzqd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zsidxgbs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcuktgf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jozrddof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyqffns.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkhnmja.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalzdvt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqpbchu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zdomgwcd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2horbindm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlycucj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sddzaagr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwfpnje.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxtxhpo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kuthpclt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjyifpm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fixwythx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfixssax.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfzioyy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpxoeix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsmmwnt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqydxbp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cciferba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrusneq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrftiuae.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnikvafr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjukzkr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbttpgx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuenmfjx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowgdify.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkggthn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvvbohz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2epkjmnql.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnceefb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqghoyyp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwvvybm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiechaal.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2diusvbdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwwlptj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzzenbq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwtrauq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmerydbh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btlkuzsh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zyosjzbx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgkqiyl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riydoofj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lspwwjvs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqmnnuw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpdyse.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdtcigy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbnfnrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyrhvsm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wygihigc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khdhtmzl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xncauhhl.html


<!-- 参考信息 -->