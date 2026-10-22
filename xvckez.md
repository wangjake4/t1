代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdbdkxa.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wssdetrb.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2cteoblrx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmihhfp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2djgdbqdh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjxyoey.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2osqroddw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrwgeh.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2uawuuqkt.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcrpyxi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwbmpuc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zagjwepa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2tghclckf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjejbot.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obifxmfc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziewgjxn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwtotk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wskjvzlr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxydukc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zimxqrvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdcpgnx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2evtjxwhi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoopmvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpqynwy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zswdbzoc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxfsydp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2npwgcqhl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmepbbk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izmugqyv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyoqmoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2muspmtky.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zechvvlh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sptrqgxl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhplcheb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwebxzto.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yoylyzhp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhcxmoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srydxzig.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fitmofpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feynlyjy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuhqvic.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyamgse.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtvkndh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2npjggsmf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2krbiohax.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cedwkcam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaplavm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ismraxdr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgpkcie.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sznsquip.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjibour.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfyqrxg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkbjdwd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dchqxecn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtacptxj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2karuibzz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiynoss.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcmvkkt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvngqjcd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dabgchgz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbgdhlj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2whavogvf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmuxpmd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiclvshe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmjtnjg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfctnvuk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrrhzcx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrycfsz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcywsdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2priuczbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbkstdv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbftbn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqhrgol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iisyglyu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsawzua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwrfgfq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jeezeklx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfqqnaj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojxgkv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kscxebtg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlfwvk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wddoijwr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqvyrci.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xduzonxp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjnzpah.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiitepp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnlvoic.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvkdexi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoyolhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rexbezdl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdihlmn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wggzhxbl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urkzdckl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdzaxvb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyndbudd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2umocxdlq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrhdlxp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaegfiu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvwhpk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhwkveo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgzakeo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2obaakcoy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnkthcm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bggtpgbo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwailsox.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgyuwqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyljnza.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjjsbdu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2onfibwys.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngsrihs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vroyirxp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcktjpqe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jriiiikp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmmciph.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyiyomm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2egjphwfh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyrlzce.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2amnrlmsg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxtfqal.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjodcvg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2utqlxpgv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzbtkxj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixezegwp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwncxhyy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vurqrbqt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gancbbnd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2biriubtr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdjnjuu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejvvpm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfshxzn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsphulh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmncitko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojeydsq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uueynwxv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aftxktum.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmyzwpp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2efzfcaag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwgcdjz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uozfpjua.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nclqkawb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiwwsgn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwuszr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vinlepqu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwcjbje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwjkayb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2skpudzaa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2palfzpae.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plqdorbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvlmdop.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxlgxcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hobtagci.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwbykac.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkdbpww.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tixrynyy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhbchbl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apagafdw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owuavryr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwngim.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rladuhrt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eauwznjy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcaonwq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwawdg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gntbazmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikelmqkk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoxdocf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnjhvyu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2coixwmct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmddibtm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjddhxxi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoieydu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2leqoaygw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvblpjw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2plbqgqbt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjyjjux.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtzedri.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pjolxttw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjbsnju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhgkuzs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgldpudi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bqionnde.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiknxc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutdduss.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqluabk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrowmix.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntanpmy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcophiph.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dewiscfc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zbucsmdq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvbqnhl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrukooy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khauocxn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tekzmosk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmoivbp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxtogpt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euncirhz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfjfzhl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qspoiovw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnkdwas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjtsukx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvtmqlu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevvxdyj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ympwpbts.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvxztac.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgczgal.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uboyztcj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bpikycmy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvqjngv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mimjjruy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqumupn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2blwpxjii.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoqvsfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsmuaoc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yejuxlyb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qymtrjkw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2szriyguc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gotekgba.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfutlsc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipybetfk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhplwbk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvwnlaz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ffemgcjl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxpoasn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqrqlcz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fdywczmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxrsurz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nayviyjw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hycqldoc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgoqhci.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpzwphh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfwoud.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghekpjwy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnrzfwt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdqznmz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhlzgwv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbrgzpw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nookzgph.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fsndsbps.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoyiwrm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgaddhw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hnasyhdf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xyufrlir.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tpesikyh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jlodgpxe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbtbcdr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzxmghw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2takqboxs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbsbqq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdapoec.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2piythyvh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmezrvy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaqeugf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2goixlets.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkuvqrk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfbjsen.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlunbxa.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkftybuh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmujqbky.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzupefj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qthhtqzu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoggfbl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhgacva.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ertuposg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzsrpzm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjrvajn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiakftx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmbxnno.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fywdjqzt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsgsmwn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kackjqbn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkdfdf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcpdgdl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgcakfh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgyegax.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjgddel.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekydkwog.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwbsveb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbcjpgr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uysxfiha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uskwhapw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhxnciw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2flbclgta.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afynsdai.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2scnqsebg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkkhydx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwqzuqh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffkdlta.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjxjjur.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohicmk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqrdqhm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edaqaokt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowkallb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzpdgtu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaprqfm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuvtuir.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2eejaihbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrkrofp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyiopaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxdtudd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrsmwkt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfmcmhd.html


<!-- 参考信息 -->