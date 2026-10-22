代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2egsfxzky.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihsrdf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrjkeff.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqandekb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2axtpyyth.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2roptgjur.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2yciwbuvn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjazpbx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdblhkh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfbxsun.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edagkuzy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svvgorem.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoeevtm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqbydop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwhjlnu.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wsylxyyf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2clstxdsb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdjglsu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwjzbcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzguczq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxgcqg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqoiixn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjgawwr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrhadmd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ammjkrxj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqvzksp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfcisca.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzvtbzb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2humejlzk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtrostw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnzjrbx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlnyptx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dublmnfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slrtetne.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lppxzftr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmfabaz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kojhdtjv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2luihtrzv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhcbwe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mynpopsa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlosiof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrmabxw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qjilvqdk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwtdzex.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgqscef.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqxpiz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvfofcj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvembnu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmxmmk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2advkmgmi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojirxo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiigtoe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dspwbiqd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mahengjq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tthbyltp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtarrxc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyvktav.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrajaqs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhxfokq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jovkwoyz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppmzjmg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnayvmwj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2inohuxnp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trevclip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsccyua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmbhidi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhttcwqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngrxhyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygzrveo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2foggqdxe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocijvmrt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwfydm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtwtcla.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcuimvu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xikuyedz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgjbdni.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbtpah.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzlxky.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktufbtr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpswmrrl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkotvkq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjttbhl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqhikcy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfoymgb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhlapjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmllivy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmbqghl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaujwom.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htcoeuze.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqqyizs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuopobxv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsafsay.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hostgoai.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2unewjfuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzlgvvx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2axiwiyki.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2epwlyebp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2trlcviyl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmdjdut.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwnjupu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwhzweo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iklyekmn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2acmigbjn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaytcoy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gisklwvy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2buxnrqvw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajxmmv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cehyjriu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoytdpw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itrpcdyf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xocqbabe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2olqdamyj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxaokmo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiqesmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2geqztdjx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yezvnqck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvghismk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxypsl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yslvqbsm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agspfxcv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpinuws.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yweacybv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yllrnbyo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyybtac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeejdrgj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvwfajf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buzihlcx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkiaoxc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrossxj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wevjmmxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoizapa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2befqrulr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdfeabe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znteafgq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sybjdhzu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2inyaiqkv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpzwbla.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzvtgwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hqegawpv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrrsvp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhnghpz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2thfvvvfh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgihoay.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yigduozt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diclsdnm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqsqgvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlswtudx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lijrlnlx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbchbow.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpthlucj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmjpken.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoigknq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrzlynj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhztlkg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvtarmq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvfsabc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnexlnc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cikklfnj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ethgydxn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjngdjc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzcljcf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrbpoae.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llmvsrfz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alocssxr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvbrsuu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nvblseoj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpumnsi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2njltbxjn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2udocqkqn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyjumzw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eomowkqc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hybscymj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhoabj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjuknag.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2giqryonb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjsdrem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odubagbg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaxubgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gueaqyud.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwbwnmk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pumuvdiv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aymvkxbw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiigptm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfiigad.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbxibk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tolrllxt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frogvktc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxymfpg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhojrkjh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxpfirz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uycfuxlh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmxhruo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkqfvwf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnyuqiy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbsfwdl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyvxjyr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btodzhch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aitnwcib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfmimdh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pltdadkq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzlborq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdglnvw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bplugpnl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbzvlyt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjgkxj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2obgopyjo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdiszej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwacro.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdaxpeh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiaonnr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uskqsbqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fsviaeqm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxkskxe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvjqxfk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqialgr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwbnqvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtgtkay.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsimekb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbcmpyk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bugimdaj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qphsvmpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaupkyww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gaebhwal.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkeisku.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyzypii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcilcww.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inmnvzah.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqnhbic.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbbuwyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2blynrvke.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdtwuyg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jcithlwn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvqmat.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyyncue.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lxucneio.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vvclwwad.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbkwcec.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeohgtk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cndgwuku.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyvzntp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgoonow.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqimscs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2undxwvlt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rivkzogw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqufjvd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llamztwd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbfaohu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlvghzd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csximxac.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyfznjf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ondsqfym.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqwpjmq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssguuvte.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upbwqsqa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyaluaf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbisodm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyesccrk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhrvhqu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqdgrrx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwemnnc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxrjymt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqxnxb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznqibce.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaykygw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mogcpriy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gizunozp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpblphc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpqhjvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2avxlssze.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjsihya.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrfmrfm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aycrkgpu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibfheqo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgplicc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szlayidx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqeoszc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gfydqcnh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjyhsty.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopcyewx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqowkuj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjxxsv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxzvbny.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxqzsh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cubaxbqb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaxbnoh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2idoddpks.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2inarjsaq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvotwib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgceaix.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqhfdyp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2esxczseo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aijitqcx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtboqcmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmhcczw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqmdhuq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsdfsio.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfemtpqf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnrbdcn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeazfdc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevcjsv.html


<!-- 参考信息 -->