代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jisnojyi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaparbu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaojpvu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcwrfcl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jonkdxvp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxrbpxy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaaaglk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxbbjvk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyhhphq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2imwytfrl.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbsyapt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dnybwidy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kflhhxsy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmkquzd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvwgpao.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfnsuse.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atugfcwp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yubgpyfr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzchfhim.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpegzsl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhgqdvr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqmrgjz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2saghbjxl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2syhrgiom.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiiuwec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2skthbxcr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcrwfks.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xplzkbes.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsndzvkd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyviroya.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bghqxohd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ggirnqyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2crnmzrhv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqdtmpx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbetvtoj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glevnkni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2blndgqdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaklvgq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2khgvwnxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmakcdzj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvslwin.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxqachw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlevuvqh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2plkiartz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2taqcrlgk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dectyfmf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2haphtndk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtswjva.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aplahahb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnvjvsb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcmkqmj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzzifzw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhhdkvx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxsmock.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkvupak.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkebnxf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkfumky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbzboov.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfwobe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvwdhmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvflytup.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrvbbjv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyxlqj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtkplkn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfetxxy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lknxuzxs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjpsye.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrqjff.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mefuyedy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvphgyqd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gggyacqq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lviushll.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehsszi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmnqlkr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzpecag.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmgqonl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2milugumv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2votzxtno.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mckpzats.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fddkduse.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvkiizo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbffgco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zifcddbv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oopojdcp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrykforn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shdqwaji.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pviudtyd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvuniez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkbmbz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqmhrko.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rknsnrci.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxzwirk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hproirst.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdlrmyq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qytyagwq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpodipf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qozsherz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkvwbtu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2riisfugr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqavwon.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqiqgic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hscxlxfe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbzlfve.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bagivgjw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyjsmcl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqqdieb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yycdswsi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbcossj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsyvana.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxakslom.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ambnjnyl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqqzxga.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdcjpuk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbndrfbn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krxvxydl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkeaywk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaueens.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbhwbnb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfiurne.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhorekbv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2doxejbqp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsgsaxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kptdaehc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeflytz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phsnaebv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvudpulg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2smjybfzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsgdtfn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2roxlbxtp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byiecwnb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjdcotf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phrocfgu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmunwxa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2guyxjpxl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwwtgdd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obtdjoeg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzzercj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiwxgwt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhckhfb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwqlmhd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2csltflku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpmbnzy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2atdxyadc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwqgyjx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uavxbjfb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsumlqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvktcjw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dyawkkse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpwapoc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uknshyrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjdcugt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ngizplqk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hylfvwha.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhegocy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzxgacn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bycuxlmg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcwottv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlutshhb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oaijmcev.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqwtqjx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjlunpt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgjfrzy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbflirtc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keggmvbv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyipqkw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqdwydc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tneyoxwr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbasvpvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjqqedq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyrywhs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vezpcjnw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkklafnl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvclsbuv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsgohcl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxikfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yaedwtoy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvvtyvt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqrfxrq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyyjocd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnrubau.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slelmwtb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcmoftg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znophipe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbldoon.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfjntjj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpkoptw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2alwludic.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2frvnuvmh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoqfzsa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbnmddk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehibfjkc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxokvce.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdokhrlh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwpkyj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdcrbru.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udsewibn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcqftlr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrojstow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzycgvxe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmorzjec.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2norkfnvy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vedncipx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfokwbn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrwhrgl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2chzprjii.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwispoz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbtkalp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpbiww.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhywjzag.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdncnmb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsysbmzs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqflqjg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jafnvire.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqpcimb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkkcxap.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyyalmx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hymdoupb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bisazsmf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpavmmrn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpeuyjh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2brkmapzg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkftsjxo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enrhjtfc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mohtsxva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2geamofeu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqheia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xembfoky.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchwvule.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgttetn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqhxzz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsncnicx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuhrkud.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfdjufc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdmsdna.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdqmkit.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2thfgtrpx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mhozijoa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhxffbk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zrptijvs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rddjzrla.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bhffpzoq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnyjbon.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vmefjhhm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhowaiw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phjrhzou.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhibgmmb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agkrnaqe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzksxgx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wfegckqr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyseuvg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iktcepck.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyviaad.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiolysi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yruhsxde.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qspwxvpa.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjduauv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysobxgdn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lovzekzc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmismpu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adojezfp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqigfpon.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2byxgjmsx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2flxctqro.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aoovwybc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2holouobl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdwjrhf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttublabn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxcruqk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkpyipb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxowpb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dogwjxef.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuxrijr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvfiime.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lllpgnuh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2irpxmobo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2drusykln.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2skaykemq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ribjbhpg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rabegoqo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goveaefk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhpbadc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbwpcrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkkkbvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpxrnfe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgnzobw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvutfjwm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jixqnbnh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwsitxi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnepzed.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxjrtti.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwsidla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwmdtbl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqsigj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlrgbbl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mdweidaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orprrnis.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhblywo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfnxszo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pyerhwmm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhvsrmx.html


<!-- 参考信息 -->