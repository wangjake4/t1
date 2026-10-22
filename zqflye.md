代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjbiwsn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enpbbloq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmakak.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyphfgwn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxjoeyd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gupsonab.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtkvupx.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbmssu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwnjsmz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cblmuqgh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tpesfthm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eksvcmzk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zussomhn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tuypukuy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nijgfjrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lpavsylp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfajqhi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzohtoxl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkymiwkt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwqqaru.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqtrljj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2otrzlyjd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrrswnx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcpcbqt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwzusbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbagdid.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qifadqma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qflwgvgh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzosuus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcfomlo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkqoim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpwwgek.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2coyrlyan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vauhyhox.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmerxdgf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgorkuyh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgquwgj.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcestxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoicolv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeiiran.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkaeedo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbjibca.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2egefuqze.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2arudmbbw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxjyuvi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftdkawb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcjcmgh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyewvjbx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bckzwcux.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyldhqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eotlrvvg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wokmhuvg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfgpwn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzicpbmi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaczrmf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfqxnts.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmadzcj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhrimjl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwphcjm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmquagws.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymunolsj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2povowexu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwqbncr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2afxojpry.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdvbtrq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2arrosjja.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyssigi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxrjyqe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okwbymvy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sguuyiya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspfword.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkvihij.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpmfijg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbzggtw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shlkbljx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qesixzzt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkfyipq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuuhubr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2argyoaka.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzgzetu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsxcoon.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arnircbm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjfmkaj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mculwlaz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2awwyjtnx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mumbotoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wunrirqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zklhccqx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmqvolr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzadxt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurvext.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ecljkxys.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijlshfz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaenuffd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycthrywh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxvgfvw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2agvxlhue.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwcgrdg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrszpwl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrogbjl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzgxbrd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyfgqzc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eghjqslw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bcugmaxw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqecxw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkupmvp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nodqsvnw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anclbwzv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjqftwp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwkvnp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbccggiq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2quedltti.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvimogk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsuitrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmexqud.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrfikug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uffgrvks.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blctvffh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eltlpnur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utkzxame.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flvnesso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dootvbay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lymywexa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfktxpwv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrzmfkb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kczlnpja.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdajubqd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjdayfq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzxggq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2orppjykw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2blhskqmz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2puubdlip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjnxmrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmmmzc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxreivd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rosgfsms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aechimem.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkyqnqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvciczwo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hjodjqwt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rcufrqhf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmkwrkc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbusefq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwjrhvk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjozaqy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkmpgrs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hccezpli.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmbbtvx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhruogos.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kewpqxpu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwcxkfr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qotgbloq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqinjng.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbctqsqu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2owlnpirk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtsirdb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjvswj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrdnccz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkcigrr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmsoias.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jysevmbc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lknmsvsw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgkhtrn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2psetukao.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iinjbzuc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjgfzqe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxgqpfw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2febmouya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivpcnc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqucnqlb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwtjqps.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hauouura.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxqyiiz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whnpkusn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2drbxkkxa.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqdeqok.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thfgfzry.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmtqcjn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbepidf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzrskwq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feesbfuh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2odhyaghp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiuqwnu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uujzchlq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nygiqtjg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxxentx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqujruh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvsnibd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmzjgz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jriowhys.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2evmwntqo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjqocwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2umhiuyrv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2moskifkj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2silzjzpq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2twkncqyf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdgtebv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2trpnwhto.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhoylok.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmrhimm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tckkxakf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwvmgrw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eztakqqa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2arpojrvz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usjkbati.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vurkyzxq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfvunfq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqrftnp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzvahoj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dehmlysl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsesqpff.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kodhjpxc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuondgi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siiuqdol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrugqxk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcgdmfs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqxnruu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmxmkza.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rctsbeso.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msweifon.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzkxgsj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrzbwzx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pymcpigs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ttueuzgw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdjpyco.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2opmrhnxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoqsebs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrynery.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbielov.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvcvzda.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqnmbsb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhurzsgi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcgsqta.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkymnfys.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvvtff.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgozwgf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjhqys.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwudmzq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiwyfka.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwkapuk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjvylqy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsumgik.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoggmsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmzflkw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqrclbb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pelolqtb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowzpug.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awhulzgy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmvwtzg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbcnimj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unkbjwrb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qppxfmjt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uxccbbej.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lypaausk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzdniye.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2muixxyit.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nprceehq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhevwse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkggzor.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uezzcwck.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihsoxx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeneacq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlsgops.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2srctbxxa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iunfgdjb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vvewcxhi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrxnypd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ageetezf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqspuuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtkqklb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtfqovq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2asolwubv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ypytssdc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrzwkky.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfndwhx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxdmbo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkfxoce.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkdqmni.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfprwnfx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhontgr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiddeqn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiecjtt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoutwxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kypyhbdk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2varhmywg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnphqnrq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2exoymhkd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdakrele.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatsgjkh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkptkoc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsofzaw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edjsvdqo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2keletaia.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyllrvo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaqfhbj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mahmuhfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrnowzj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opaxnpvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlgxdqy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzboggig.html


<!-- 参考信息 -->