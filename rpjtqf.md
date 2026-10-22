代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2qimpafra.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzeeozw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lccbvasb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xacvzwhn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhasbmd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kunetxjx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnagmgsv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfeemxh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcshyznc.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jndklpcp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiizpvu.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrdixpf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nkavsuua.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqkzjfm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2syergfoe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2okvobnjh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qztsygij.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2giibkpzt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyhhvlk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uuldtdlx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnoszfh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2znduvatc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwlessu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jultfthn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kszfnwzl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmseochk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdocyojx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkwtihd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkerwck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2goxdohtv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2scqxnlak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jthnbfpl.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxnhykh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sutsexjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkzwrih.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rnucxzcd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vurdmmeo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bljymuwm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2eceudfkr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpbhyiz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djsxzjyk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tersqeao.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxhvfhj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbcieso.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axgjbpyp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnaucta.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnvbhky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvsadxo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwicofb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrazmif.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2inweirqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cldgjoch.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdsqrue.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjilati.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2msbmejui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaugvexb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2suawjtyp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkedwouz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2filsgjxd.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlogikst.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbjcsrs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucweylob.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfqubml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2horqqfzk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoizptz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkzqvhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjdpscb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2foorqehc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vrncvptm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjstnqc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbeqsvn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctqmwll.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aosbokzd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mehuplqo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonwtnc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glmmreks.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqnwctc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lggqrgzo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oktwwijg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lldsthee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoauhzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uekqmuqf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxspyd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvveayv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwotrlz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uckyroxz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjwxadi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2slgksonv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2meuukqtt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqluzwxw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqiyvu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pizzfrxz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjgnnhy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjsizif.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2myafjbft.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaweifk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcyvlim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujndosu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uypnuuci.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrykmny.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2escjbaqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyczgaq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dshszkwm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcwoxcu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cdthiqcv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbzmynt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjusmdji.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqliarm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jbggxdno.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzowgywq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvzlwoi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcmcele.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzcxra.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfidbwp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrjnswm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtxdqf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoolmop.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsqvucx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqnxieg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdgccem.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiraealg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psaqrcxz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2boaodfli.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfrrcn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2alemnfmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvflvvpj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etqdovkj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2euoefpzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrfigkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrinzjrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqylgdym.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tehhtnpz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtsbojo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjatrgo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tyakpdzs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iwocsdgo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eozmonja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2atzvgfaw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqzzfjt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wblqppsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laaasdbt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oxryaruc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tklkofrt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyjrphu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssfpkt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdkgdcm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlsrhsa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwigemp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dutfmubc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvrkdoy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzpzksi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rudrvqnw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhipwtuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iaplrtqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sftrkjam.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dendtrxx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxssepmt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucriieqx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpzwewc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvdybbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssliggup.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qutnjvya.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2teebrjnk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmidfftt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dciqxkre.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbkzffj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nquacsha.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdusei.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yymvcmfh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2axjirtyv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdbcsqj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyxmpcx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhixvhn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qicryuvo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsfrjxa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ritbyuub.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjugxxbl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eztquoux.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnivkmlk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyuzdnf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zggzjsng.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqndotc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itnkblbc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrrclyi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdormec.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2utvewude.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkblur.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxpueaw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrsgapr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2augwrbbz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpcumib.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osrxykir.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxqhbbz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnocpuf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jfruvoub.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sifbkfdj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uteeurle.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uojgaihy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhesxez.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vadrwlwe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urrwncsc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxropmcw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlrbbom.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jruwheks.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkvuvyw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2avvekqag.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwwsrnp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2blykrisk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdincbog.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtrldoo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnrbsax.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlswufuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwcbdtl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnlolwy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtlxwzj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oeidgppn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dylivywb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kegxhlha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvhvriu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgikgfpq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvdpxya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yurhmvqa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqlagbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvrabvv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2trupqmmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsevuzw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hesoikeg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2psjkulth.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuwejmu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyollmn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhnshdy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xytfifvz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2juovmfrw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnonkti.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mphhmmlg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiavbio.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyathbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inacmapu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdqzban.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2phkckffe.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwontow.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niyemmev.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frphxdct.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkobrla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyqhdix.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsnehei.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwatjjsg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgfnfmb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xflnstso.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypsirr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsgjnln.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsfmuwv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzumnvg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrdjuha.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rskledpx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjkrlye.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xfymzdof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2modqzowb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxjxzvw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fookwrzt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cythonhm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbmqntp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zogwrxpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nooouoej.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfeqktf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keqellzw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvzgrgj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ficysbxx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcktsun.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kadgpvbs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfttckh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdeljv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kohlxgmt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfnwads.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcrbftd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2odfnhqfp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2unvwrbat.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sefddjvq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvtnsv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzuzhcs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqorpcal.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqffpzxo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqdvasx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnknhiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgpettx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jhubmntw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hygulfxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iufsghej.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbadbcaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cshcqryg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lzposxjl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoblkxg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apmcpqoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edggsuir.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amsjnwls.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhaqyll.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bulltlax.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkvcuuy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emczaduv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfqowej.html


<!-- 参考信息 -->