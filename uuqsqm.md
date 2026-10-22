代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2oerymmeo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpejwtj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gymglgvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmygipnw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgekijl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2krbnfedt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsygtjg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvlmhgj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2guqmtcaz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nszivwzf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qxguexvy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fzavapvm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ksunsuhl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwihclx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pxscietv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnqlnyh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeeumbs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrredthd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmazwqaw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yidtecja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzbdadw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuileqmr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmanoht.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evdiojzg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kofpznyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csljijgw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2crotmmuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsnphrr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlemjwaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2awtobimb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzraxoxd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2acwfrleo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsjzbww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hywivnfy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2pumfzkcu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qihllhdx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2epfhsqhe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aytsqiel.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhtjnoo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lywxrnlx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dayzpaej.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waulfyjg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2paodtenx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2klpolgrz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbangsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaosnxe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpvlkeh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwyxxtk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2logxaooc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivfwyjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bitwpwve.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xymdboex.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjutpxgc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kucgsfta.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwonuzsj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzyougz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtlqhz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlsifgp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdobbsv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2htebttlr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2danfjpcf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2regrcvkx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdugyhw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgxkoe.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfqwmwx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kffqrbog.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlptefbs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgeuhgk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdjxogi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pztkxzrt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfknlec.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgipbgde.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjamleh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieosexwl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyadhbww.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiwcegv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jycbgtnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbukqafd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxolbh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsryqjyc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrqlsjj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfkvazb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrexdfl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsuldpv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuairugg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lchleftd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfzuhqm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2opxnermi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckqhhjw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2brnqxnqo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfswlrzj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jxstvoff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbigedx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaixdtsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnfkiuf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kieyphrv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwfpjv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2covttfnb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhwzrmr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2alphugpf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjtocvf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xncirggs.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgsfozv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bupbytmn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmvvbfj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bghbwkok.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2espmhrhz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2richxazu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2npmeczyu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotfcua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpkysqp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyevocl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agkzdxtz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgvfoje.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxtkutl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrcrlqj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuhzeds.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxbngcq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vajepdhf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2joajzaom.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hscffroq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhmqixs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoudopf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkudggt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqkdil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpdgbeg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrrhdxs.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxxvlin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirveqep.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvrewia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaxudys.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzpmrxm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sbotpcmz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rinfnkhc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcuvhyc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtgonkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxzqpry.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uokqznzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqprmtcx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jabtybci.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoptwep.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofphneeo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyhddbr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqnxaze.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsjlyzz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzqwbtq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oegtpplr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxekmqo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhjktta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2whalfzmn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqgnlcr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyugdhis.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbhhpwl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ildyufir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyuoeut.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtfvvpm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jofucomf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqlvnim.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfflncnj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uligjwgc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2brhxbkyg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyuztqo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bclttgsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeawmxj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rodyifbu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnogwcz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfqoqjk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjwhrpq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayucyejl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfawrdg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvbsenc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkeqkbz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdonzcjp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuefmlx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfethqx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rymtixwq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxlkmgh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqetqz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqcmahs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnjlwhs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxbihcb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eswjofiy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ighawkjj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrhrnai.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlgrrro.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dliogqqe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihurzzf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rugxsipf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukocvrf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucntyodq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplxmwk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzsvksj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwxfksq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtafzlq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2erbjkhsd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiilhxf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhyzwh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2evoehmcc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2osukyqry.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bktvuyis.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rssicapu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwmsxrd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohmbdh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlsensi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fozryhmj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjgimrm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wumbjspj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhvugyy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgslqzu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bixychmd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bumpbjdl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sifvkiar.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vfphupla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyaxtzh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2noynsgpt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmieilx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefrkciy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqtised.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwwpgyg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuwtmwv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdnrera.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctowxavb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqfbtib.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeecyuo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mokyzyfw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2owdgxbge.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cppotvxu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jtonpbnt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxytbyc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnndqyl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmqnwto.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxodguq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhvodvy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swzzpsyy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmftpflf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fphuvhll.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2diefhgej.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomzjusw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgypujup.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpctyny.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siplqzyc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcbxctn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sskrgvcg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxnyvbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkzptdp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxuwgii.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmldfqbc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txqvgrnc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2knaxagfg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2crfopppt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcplwht.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2duaoczjf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwkwsex.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqrxplw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpklfmlo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdkgxrg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qinhohxb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2odkqzrvm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwkvqjt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2alptdwze.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvvylmg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhoqxyk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrtlrtr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsfdrbd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhrgihb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzjnndx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hxffgbgy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egavyend.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2veysbone.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvdklkv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrqxspk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtxkwux.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsefxdf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcyjpyu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2chlcuewb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxnaci.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2weereldm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqolhxfk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihonqwln.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuolwsdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiccxnk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2abkyitzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cyocfrkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtfvitn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qikiiige.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyzioyc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgocvqt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2izxrrqqx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewicejoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgugduso.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvpsesw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzqnjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tomcrcvo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giqxrdxw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzicmcp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fnovmjas.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xntpyqyc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmpssde.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igricjxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxrvdrs.html


<!-- 参考信息 -->