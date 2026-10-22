代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2waahhsge.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2znkeyqhp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wikxpxlf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2spiwksub.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsctckc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbsweiu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoqlmhf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dghsrccu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkmffks.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2budnabye.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsbhfuz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdtqxhm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzaopox.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsueljl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbatklik.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xvojggoo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vblgsrdr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2khnvvfti.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwamkb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzfkhfy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfumea.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xekupooh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaeqrnd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjvcavp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvtvgcq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jroiicgz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkhedw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjfkynb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtgzrva.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeufudp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvjvmrh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wljwkofm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vewustfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xptlxtle.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqmzdvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuwfksw.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgxmkd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrefmnze.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enkymphp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjjzgzh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dufcozeu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwzpxrb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxvpnqr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbokre.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxliqvb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxqrtl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqpvrc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdthjpyq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoljsipd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwholwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkycrmfl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvaamwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2onquvops.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfeakzo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kssagqgx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcugdag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfwkrlz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aacogrbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iofqxwul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfewivu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2thurbjsg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzftpeox.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdppcpdk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krpkoftj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzrpmll.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iksacety.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcsavhs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcigaix.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcpxgxb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwpzfd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2taatahoc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcximmf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsmiev.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpktpoee.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wytloipp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tagedngv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsaftmj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2maytaawe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrclwfa.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awhvnlmp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gglqgpkc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiknpit.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kamtqkck.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2skaxkkrt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaacqpf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nafluyxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxslhva.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osgewfci.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrcrxjo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbzsrtc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdvbqcu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvvvgtg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfajxctb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgscvzqz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgdksep.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzxjxtp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzctaipx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjursyvt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyorfdrr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjakci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxecog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whqafupu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yglbiurt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nldcuvsb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jezluywu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyfpnbs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplunmdw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlvlyae.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnyddxn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqbksbt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eubipomu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyvkdsi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzmngid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srpnleer.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwpqlfb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okoscmvr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxuzlmy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqeipo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadqzyit.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdfycsa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otwdnfbg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knkxvcxr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjitwom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onqtrcxp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmpszob.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkewopa.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxselbfw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhovbag.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwrnfdb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjnatov.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmomigqg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmqhiti.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wipsivio.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exjtvcsh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vppuxfmb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2njrxjwmx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrxjeum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbsskee.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2glhaefse.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yotjjoaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvjzmpa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2foisdaur.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nijrskey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpbncbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stcbbqww.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2onuvwqiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaphbpiz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xsryrjtf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sadeeepb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjscmuyx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaooosue.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtskyuph.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bahssvpa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2btzeytzf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krpywklc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqngnjpf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxkrcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfasvzq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slvcxftf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ercksxbl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkzejbz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbeqvmv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghizpjlo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjtbtit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcogldp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbltnct.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzltedp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qebntgwi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wilmdpog.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqgkqex.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2edmwbpsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyagpnk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2juljxtgf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2irwdljlb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eszojshf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkzqlwu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotsrmvw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etfzgoeu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvipkni.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omazbtwn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxizlzb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilposknd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mweabmdz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjmhkrn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgzpdni.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqzmzxy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtctmaik.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nehqxmxf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoyvjpp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2alpjscsx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhcdevo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atcxcbir.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdkwtcj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypypxqkh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkodugby.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyutinrs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailsjgmm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcganc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nssdmiky.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apffgywo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lffhsffj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwxlzp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2miqrtxon.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzntpbj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2icblmoqt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxuhiyj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvgguzr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfitwpy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsblfcy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbahyacq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnvymus.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnacgov.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqvnyjd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmxvhcx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyvwqpd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epbkdegm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvmrsg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svtznovx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lszusors.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2osyouxvv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vreygghc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdoovyr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpzbdke.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emingdyd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xahnjwfa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixehujzq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuftonz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vknzbhhf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dzliolpm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtykiigp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydjmqb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2plqojsvw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdvchzc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mxntrlht.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2whsxlvlm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvhcjii.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mendbmbz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcmrzs.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxfhelb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvacgxx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtjwyxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqotccxe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwiagi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgrwvse.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bslfbvpg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhihoqv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2degdqhjg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsmjmsy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2debsalcr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkazdbu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulefraaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srkoctag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcfofiy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyssqtg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvjyahs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oiibvlbh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifencdgt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fngigftc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hsydroic.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtazpkh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2urgsvxwd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcoqqgu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcqrpcx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xizccngo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdmjrnv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dblrhcgf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbrqwlz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzuunvh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2shivzkrp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjckmjm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnatyuu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jqachgnl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmtctto.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqjnju.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzndslqr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vibykvpf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqybtyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrxccms.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkowrmj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingnvzsn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmjrwhl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilgiqyy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoabmyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2acdpdsar.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqpsjll.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ityvxglr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnnrjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2orgjiqjw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrzkczh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2trddlgbk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgqmisc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hswtmdma.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrsildy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crodsutd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kexopetd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlvgbds.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrrbnji.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoqdwgo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkfxzhr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdwsih.html


<!-- 参考信息 -->