代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdkozew.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2chbuecrp.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwpnkhl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmerklz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfrjfhx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzmjyy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrrxiny.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwkrfpg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgilys.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjlrhsn.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnaoblv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfexqbv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcuauhi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rinpheue.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dunaxeih.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkqglgr.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxqqkfj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vflgfudz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbexembc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvcpkt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2epfbbwbw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sczxdtzp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbigfga.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaqfrqn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qmroxacq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgibqrl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2atlvtzdl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vozppwiw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sywueale.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemvacrd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlubitb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpjdyzd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfqjpoe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ricclopb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzdljtt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2urvnmvwe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2duqpwrby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyfuwtk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zbajyfgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnvodc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epywgdog.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2unjpxtyw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iiazchob.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2exxrnirx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbenqdxv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwqjeta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkxcjwu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxywyavu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpjnycd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxzgvoc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fabzopxs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wunlrfml.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kusbcrhr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imfzbwfu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlvzixs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxsyaht.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2biyccrqf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imugqlno.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvtuxif.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmuqula.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzaqkqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvegpewa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwqouc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jarihfzj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gktdwrpu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2secjprjn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkizxeg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akzeipzm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkzlgxj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzujues.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2inombxzd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjtfgit.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2olgstulh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhgtdqe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfktnueg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfycipou.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jofhsdwd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoaaypa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnnbrh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amrdveyi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkipwtom.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggovkhhn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2styhqxso.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xznxrxgo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anvllepa.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtgamy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyishpb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkexdclb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhhhqya.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsktyzfu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqdarwk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2orblndes.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgbbcyz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lndibnla.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfhqohm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbfzoqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhaasll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gusyqscf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkqdoei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrakkisu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezozlqo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2glwvaqwf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbhwvja.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwqkosf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuubymrc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjycotar.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yywukquz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2emjuuevt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpcnvhc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhohbai.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyajqire.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxcuwdx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2caxlblrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byosgmad.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2icxeqayg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjduumw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpqdgjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2agchtwzm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dffouacz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdxhfyv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzrvopc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkkynoa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxkwbhw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2urrpywau.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoskwwsk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cexpbtzb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vworejhv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evziayvx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmsemdy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsxkvwo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flocrsup.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzldrlu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qedxalfq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmcbnmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peyuojxr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hinobthc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sseplshj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjaqugi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcnuqhh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oskfzaxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zezpuxuh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgdqvws.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkfgfn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvakqpc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ndanlhaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sghijjvj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewahqlbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmoxqsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmgubnp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvjicxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ionefjql.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoizogh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjwiewc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlglutn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knycpjfa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gelrdbns.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvipulen.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvugghj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxpnavz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoikaic.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2javnoggc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwhalmb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tulxovvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysoxly.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2losuffps.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwxwgov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfhhsvy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnimhzgd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxlwsbr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvroaabg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyqnqsu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyztaov.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtcmiql.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2plednkkf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbfixrv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmjwncb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2scsxkwap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwualco.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtncuhdg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdssjoy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxuexoc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkahhbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdgynlu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqupnazg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzquvsb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvpmrfs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmxgbly.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbrnalh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2diiiclli.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyqrubn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pubxrkkp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeskekq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nymbtfvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2deosclif.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfifwrut.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkuzotb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwxuahe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jphwstsz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrinwxu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkjmbdb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxbppho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqojmbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2arokjfnf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiccqbx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2arspnosa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iblvooth.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuudeato.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnkknkr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwveuvu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2neaxcmbs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwffjyg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnnhbsw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fehtrqnb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmxrwtt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aernbapd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yjculdwn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwanmgrb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdtyxwz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjdzvnu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrbiepr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gngsvfhg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cthapfsl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swpkoija.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oycdatuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdkcmet.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iguwztcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxwumnb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoturugn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orsgtwez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpogibik.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgflbspq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnbhvey.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdeflsy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpczzpg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nowxhxif.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtkvheo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2visdndbm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrghkak.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqdzxwr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2botzmvlg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxlgrh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lleeetaf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhycvgy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyrsqbf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccczsolh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzorrqb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiljkuo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjwkttv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mozpymsd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twlpigbk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2woffuqte.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zshtptmo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftsoacu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjwiwdr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bapgunzd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvlkygc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqmepkt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhetkoyf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nepwlnbn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uaufkumd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmktzbt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2soxolfvx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqhxcro.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvprbop.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjyvulu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xrefzwvn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwefigp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jftllxbg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2atuqqpqp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnuwbas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yaatpahq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrpwqmn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vojxwton.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmowknj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuiiwnu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cukusjza.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2avjgginp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvomnrhu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyjvpew.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwarjhuu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwscdyn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvijeuhv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlswvvot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkaxhyw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzvnzmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcoleqi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxioqzl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqikfp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsepwukn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocxknhg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbfdeqf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvbdler.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uubvpepy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfghqpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cewlhfvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whqfubvz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbqhmwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoicwxq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmrmxj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpedmksp.html


<!-- 参考信息 -->