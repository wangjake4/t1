代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcbkmmk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puvzxidw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtgkkoh.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqxalac.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irhiewtg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fraqroig.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwktnmar.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzbtcpu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gcotsvop.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2epwstwkt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkomspd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzbboqj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fscfhtwm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhrpuru.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuhxtqq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkwtcqs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2drvzzksi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvhhfze.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbgxrki.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2waqipxar.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhpqru.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2djupgghp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eypqnwds.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqlfsmw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjldgfcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkuunc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrixqsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umekdied.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaewoby.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeywaaz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdavssqf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqfrhdq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaukpfw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaegnhy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rhexfyyd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmprsrpo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugotcpce.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zothjcgi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaerdjq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqeucqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhftyncg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcuasqa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkridfzv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2molkyodl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznmuoah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lckaatzr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhklvqdd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2plbuellj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkxdrvy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2naocqtjm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tenrernz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwczadel.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2txvvawbl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqisiin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ituxajtb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adrgjucp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiebrgn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgaumqr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2strgekyd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvhsauc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijupbgt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkjdqf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cocvmexq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbvwdsg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqmsukr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzrsyzc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2snktexkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oytelobc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksezwynk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfilpsm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fidndxqi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2likvpcli.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoegvxqc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sagfaplt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpcmpxc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjtsur.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utesjcrg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvkalnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvbntuj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqumnwrr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrczous.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqctpqsa.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrqhxko.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2buscuzsm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlcnjci.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhbmchg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdkrkev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vssceycp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotllwha.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyierdy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uolkxkws.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrwjnx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvgkxso.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udxzkhlp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdynrcz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjtjzqs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtcjsma.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkdrooh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvwiewy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijibmdro.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvpowlw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfyuutc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwisfsp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcmrfcq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cphzofin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfhptln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2orptomjv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdmunfe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaohncw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2oqppxqxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcndbquq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfkiazs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2niajqtaq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kljlhylp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjdjpur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbkudtr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsuttag.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzzqlhq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uemszywi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyvutip.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjtpoac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnbcwit.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fscjaghf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fettfchy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2omijorqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqiffjs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvkgdfy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrxdtpx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhaecjr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2itkewski.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jecgyuen.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqdljtg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzpitn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcpmwpp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oejmqjsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ujumwzci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmoawip.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2inxqmhow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keejmdfs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jddnmveb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfdyugy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsoczij.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axeheqcd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwigoka.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvjmgft.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthbljax.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djlupmwu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xobuyiog.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuiwtbm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dutwpxxq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwdeccr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvirnxuy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbidqfa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmntknml.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxmzxnz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsucrao.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zddghjwp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wiluahap.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dglnwcgu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqtqemw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxpesa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrnkske.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gazjhhor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzqbblv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbhzwgp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2esfntboe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrulhdig.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2owviezxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjcuztk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgihphgg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alenqjcf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuzgiyd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prirgyip.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoieaqfo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbcvfg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxvdave.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzlwzwd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgtvzby.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsgjznp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nankbvvh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kitqhler.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnfayrl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brbmhvay.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oomevarm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvsidit.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqprmlv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unmsqteu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsvfibt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osonhdzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2karwydnk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2krqxmjzt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxkkcvg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcffiaf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqutktc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmkzhfy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekygyvis.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsjhhdt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2izphtbhd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbadli.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgqxgpu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uigdgrli.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlwlqfw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2czcsjlgg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2atnzbxfi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwoqqxi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yogemelh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhhkuwl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjhtikt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuchmvjp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dliiilak.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebexmlul.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdxymv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqqrdvj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaeeqiq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwolrjz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkavnlsw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidhhrkd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbjendx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmrkhhl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhgguuq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlljfdyw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoccbll.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcocaow.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2edqhwdqw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cmivliam.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2spdpzshq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iwndtrlh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aemkpzgv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdmozdm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fibcepbw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sngmfztn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxlcsrp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icoujcsr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbyoloz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlhdwgj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckifbjyx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dazrrfsi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrfrece.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhpcxdy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyzbcpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuemztt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqqisvr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxwycjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdqqnr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipdcmnz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmjhzma.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaybiix.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2quaakxxo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqyxhic.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jqglmwlk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvfphar.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2guotfykt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdmvbie.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2faypntsd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnldqwxd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mtayjzhf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2szcswngf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhxnzql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qahfkcit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgomumoo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfntylv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flxlkhsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2prsaspfy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpjslzs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2weksqvoz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfeqqum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqtgnrs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpbsmp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uiewkizi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowxzwxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpolrhy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzogdipc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnlbhhw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmnbacj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sawptmcy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsxqwsj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuxpcvf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyxqmpv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyvtsgj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iizsfyhy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lpywbhcm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlvfprx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrbyhwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zehskrjh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uziveash.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkifjivl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwvaucg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwowel.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaqmtjf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkokdjg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxmadmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomvzxol.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqrfsle.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwcwnqj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdchffa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2srzklqrg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2angkqjmh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoddnkes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdumkoem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qstutlgs.html


<!-- 参考信息 -->