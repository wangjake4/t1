代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkgarfi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2syzkvqps.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjrubpi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbnejwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kedmeqrb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sislyqdf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiiezpu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdimwxy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pikopthp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlihxag.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igmthjtk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2trxmsvps.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcmhis.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dktsqgne.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzfxhhu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxtfhjm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tbimzbza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2castanvp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cczuadmp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2veqszseh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxlxcse.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwshxrdf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvvkbgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbwrjgk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnblau.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqxkjzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkhukfi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdnzdhw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2safuysck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blmnqtfn.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lignnlae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzopjm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxhfwpz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fijjwtyy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjptehpz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2frnzfqxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdulljz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2idaenbrx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqnehpu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xysnypwa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pugmnorg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqxrmep.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cemulack.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kulkurdq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukevigsx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvushkkt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldorafwk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgrtkmx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehoafbw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdsdttc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fysvqdhq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewdfnt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrtsfxy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyvgkmb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgmmhgp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrtltip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpzdczg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnsxbxt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnoiarr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2coqzxwqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwfvryt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2meacnrjh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rutcvavy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjoeiyt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirwarxp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2usfdwxkl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjzjcmn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxcowbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiexjzh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjlxonj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tenatvxz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfgctqi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjyphwr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyngskb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2paqcxzoq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnidofrg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfbktmt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnuwdoy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpothrd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zulmyrdr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nymeyfmk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfogrcoo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgadyusz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoiabhp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uboehnuh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwepmpbw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqggkggd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmsxecl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrjgzk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tuajzxnj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ylygdfac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2whdjwyik.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlobtuxd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rperwrhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvopvug.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xztygigr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqitmnsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpuvdbz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cncvwlbp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfpgvjr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbqdfhg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiblpkv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aukhhkzx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2megkjljh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2udukwdjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkimwbv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqjlrfz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pghadtby.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyysrew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrapgajm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2malsnuez.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpctwzys.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuilras.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2veecoamg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrwooof.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oggmraje.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivcdtz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovweqhah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqpsshw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqojwzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npxcdoqj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjktbio.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkkjtxu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atobbxex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtktqcgf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuuxqlk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocktghri.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshucjko.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hushkjkl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfujznx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2howofrmr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyfqrwm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tokuyiqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2evxeglis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuzdltu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fbabzqgk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tklcqlth.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bcymlfah.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2unghqayb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zeglimqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuskbdy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcimmpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dndyjqsy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nsepkesc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tanpnmyp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2limunxfs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxrxrqx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essnfzgl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkgkyr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgeuyfx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aninjmzj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oihgwvlq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdnzrbe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2snmucevm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaueral.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2catlmbsn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhfcmho.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhitzxo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafxmqlh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2istwsrvw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwgxnhf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwykrou.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcikaii.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdaaqnj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2adzswpmm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqfhdai.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2liwfthbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfydtsg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjivuos.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eowotnmv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbphjng.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfaergm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvtjjfi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrquyqjz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quylixwt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoabldh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlduzwyg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfgbhyl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2obzgfcmc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2inesivug.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2luxjrwlk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyibtrst.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmkyaho.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llncdwld.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edmalffd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkwyskm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipccermp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouupysru.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyawsay.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzhhwgo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqpdjwc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjhvwkg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgggvhpk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idedclvn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwehwbk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrndvdb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2anqywitu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsuxlkx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjehwfr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdscdfn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdnlihr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdnijgz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyszwnn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2audsukow.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2saybxgzj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrsuzbz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omdebbci.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2igivnzmc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfryzfa.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iogipgdr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpdfdpf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fojltrms.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeilnrq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvnrwii.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxxibfk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoigcis.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlysaiq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrzqqph.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wpugemum.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zirctxxk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsegpgxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgudbft.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uglochba.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiwqufp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ayewvilv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mipwgjms.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyctdwj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mupoqrul.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2boekivse.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoenxpx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xkykrikj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiwiqwi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdkevvg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxvjge.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cschozoc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amrmmkph.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlnepav.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjocxlo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszrrazf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyqahqo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2otchchus.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spfbxxkp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lphsczla.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwqpfk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidipvm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhibpie.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eovquxth.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqmqxin.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2txikvhoa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mprdjhxl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjyrjk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmxwoe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vixycier.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlcmjuk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jaytvvud.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiijzqn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2udceorzs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2inkhhnth.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jipqibpm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bxraaisf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdjoodk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoctkjy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjdvwuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aosojlpw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmszyax.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vobkxvko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxxsmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpxcfdo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypghek.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iozutksu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2powgzqvh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqoarli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zeofblru.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgbndyg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbxirjp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2apcnryeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzimjvh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmzvhed.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdgervh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaixsuh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdybmbk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwxysmw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxjdwqo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2awikheur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qivozpxp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgexpo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yccxhjcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osbtpnsh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cymqbvdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnjegbi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrhpykb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzryeooq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoyjkvs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnicyjm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwvzvn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaveeuhy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhyoxqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmzxvcb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvijuje.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2foplgeju.html


<!-- 参考信息 -->