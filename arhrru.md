代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2iskvtojx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktltjqvd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbfkkjv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zedlxwww.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhdxwcu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xictyfrm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nipyvsrs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdypyqh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdtpjwh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwrgpl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkxvby.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbnspzj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aikbamge.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhylhg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlwuhso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeqgyuv.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxdnbcu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhginbdq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdxptmo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jzigshpn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ureikrrm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdmhzur.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gngjdhws.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mkueyquk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tygkjmcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meetiozw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ymecuqjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhmucgh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twdogffv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2aewjuvkg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmetrayz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bbspuffh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdeynmt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2affczvxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzvolxl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnyogww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lerjrhal.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeqslqd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2aaefnyhm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrombtd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnyozjl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxjosud.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eagsefqx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htriuvuy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrwrhhb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alexumbi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sixqtgdj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqwwgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfkrcwb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gohxnykj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdfahrx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2etrhmbhh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsueekwi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdgmiyn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2czddfcvq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmfmmbj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhvyqjh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkzzzhi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcvyzjc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2itchussz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpvttlt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwabkpjb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqptyhhh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmopzvq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwmubaf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2purnznyl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zomwhqtf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqwodfr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmywswar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmymep.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgnvus.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oerkecdc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuomcjyn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjssnvo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbabbax.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bltlupkm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkcorhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcdimyu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2suwhgkak.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaagfjev.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hduusssg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2diqherwq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxbqxyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbzeebr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aacjbfpw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2siukpccx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcyxwvd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvodaebg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsopabhc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlbvuak.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2blbmuspl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuckeuj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oviqgsks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihbfuci.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifglfsbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwksmctf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqiphtk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2opetffee.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhohnih.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrsgejk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vegwtwuw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnswlkow.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyzbxjh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eodkeduo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpztojj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhorywqa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwzpzj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2noqoibke.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmoctpq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbqtlxj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amatarwa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjxyzzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avkcqhov.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgapwrrw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2daohejlh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjvstfy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvnzybr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbdmxxf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smfttzlu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcjxpgq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ceudmwka.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucmupsk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgznkafd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlboofmn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2oqebsjes.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yogpcmyf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsxfwmc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xowunqqn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkxygcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2aoolemyt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qdduytvt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2afknztaj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fyplndpq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wogtyqgv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2orfemtoo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrgsowl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbyojbf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvbdngu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffagvssk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxztcwo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nijazgxt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldikbckl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aczskrnf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzrriva.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeecbjx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2skjluqyh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtwhwfi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adlsknpq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qweafedb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zyshajzi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2espsldfq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjqqes.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkujkntb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwsvwqg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmepphrh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgrbouw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eweefnpz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhtmefe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjpnwmf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbewcxuv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmubmdpe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcnvbmj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cavkyqto.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wivatbam.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbusnmv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2naobqsol.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcivsupx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2splcydyp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfllrjys.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywdlhrw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaueqnn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olufyjaf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnalqcce.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iozabmvo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqjuxpz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hekrgrkv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hspggvee.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfvytiu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqumxps.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmfgrn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esnvjwxx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zeptyomd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtoycjp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfummtc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2csyczdvb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmzpilq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhtilln.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycobont.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zusejcrr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkspgjjm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwbojjk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hodlqppu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywowlzxo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qipbwqex.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuoqcac.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpedwhhq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2syfcezbs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvpchkk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iumesjcv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odteszvo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfbdptq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdidcrz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlopdxu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhhawhi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlaxdij.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foahgjgr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulctatoz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clgowoya.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2swjrmnwq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfphwlt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbnakkz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdzzqyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fskthyvy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvyuytv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwghymw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzvknuh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvferhg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjktlxpy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqodnqik.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwayxqta.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnnypv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyicfihx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2odqyfgue.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xxetbrqq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzagzfx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfkmbmq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bdehrhlw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvesarjf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cldnyrqc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2svkpcsww.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2udumjrxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utyhtsvt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelyuwsh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dacgjcjx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnjvour.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qemaotoq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohxkna.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtskqrv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chvegbqx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zddciuns.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouarflqt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yugudkaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2menwckmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmqdwuo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdvdjar.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vezsqeit.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbbvpjo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzpvten.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiipadbh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2obdjfllu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2poewbgdk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfhvivo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfeukuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ailwhdtp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgelcqt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbpikvf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyzdoqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfymodw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yzflvapx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxzqwve.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuenkol.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeebpqzj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtsbyis.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvplkyo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfvblez.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmxmquo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lykuwtll.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glgihixe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqpbna.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvogviu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkxrazm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvvsmxy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhdlwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtbzlqn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2txbqzmse.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bxurrgzq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bltyebgt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsxstrp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgqbcld.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2luedecyz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gizvurfw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2seejboip.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tzavtjgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsqzzlq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndivro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ridaebmg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pohtoqiu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdljkcwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwwgtpz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2licmjgad.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbqnmnl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcldhuyo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hlygpceb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nleunkwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdqjxav.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uapzunpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdzistz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmewydj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkhxipb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmbofgd.html


<!-- 参考信息 -->