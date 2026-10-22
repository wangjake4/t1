代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2coibjmrf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqlntrr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odouxqvb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahamgydc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tygkbgoh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxgitqd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsngsjv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqigtob.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2suinvrje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijofanbe.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkvbkwc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyktzuq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsbzyyl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vryjgmar.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uklwgyqp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwaensa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2helegjfm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wecdopxx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hrebfmsc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxkwzc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nivrqand.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwktmoyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tkexfjyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rrneheis.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lohrpvvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmjpzmp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2idqihkoy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgmezc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhebkkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2czorivzm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmatdez.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmgylcj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhncmpux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgninwlh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2caqdroxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kemnqdzc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fczsmxji.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fphdhmxd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eurankcm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqthaed.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknjykhx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxqxfj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhyrclg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeppfgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2szejpqug.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwdizef.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bapjxxkc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaqvzyq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aphdcnhh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tceqrxes.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymljbkq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdierhi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2xecdekad.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxezprw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdtdjxy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqrlaqi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvxcbog.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtjbqbu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2apdzuznh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhmoizm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2efibsqjw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuyaww.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhovnav.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smkdiknk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2guxwfdgz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzehpzyf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpmeghx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnlelws.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcdklcp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbikgtc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2egxuqouv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqksvwu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uabghncw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxlqllw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbainps.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfggpxj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyzgkkp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtczvzfm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2enldsxih.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzgjwwr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lprxkugn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atvkzbwh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiusfiv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uestnzni.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bktslkrk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyngssfp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vifwynkx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuippfui.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhcghfa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcxenvs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fglbbhjo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnjcdxw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxkotnu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tdthbtdr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuyuisn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoymrie.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiysupp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2truibcfg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hktmxcpa.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwoaatn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxthurec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivakclys.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2muvfitra.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjaahxp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntiusjf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpvxyzt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkxijai.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwctrsfj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bycogmeg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrtlnmk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjfazjg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhlkjdv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2alepjeiy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrrkihu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgqbckq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvktzil.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqxekvn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxleuyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boqrvalx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqlqikb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcbzibs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiqscch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmzoagc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2annudwnv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxatagz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clvsfytv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrswjmw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unqsagke.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsydahy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svsjycci.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxftmpf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjeuam.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kumiwqlp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrtddte.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptnvxx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2onseprzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbwiaka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2irwalwyy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzuwjdl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2unrrtedw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbazepx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvawzgq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdvqfqg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtwpnxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkvueid.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxxykmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpluewst.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjngwpq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2icgphhcc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpkulyu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupmvfg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meolnbxx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unlnsvlv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhxpikv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zutknfni.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trxopjau.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmphivj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiirvnr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdabfbe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bashokgu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyubmast.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqxedx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lutxlxlb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjbjzym.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnjcssk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfizhdi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2plewmtyn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbszgkwy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2imfyvxoy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzncire.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2emnxtyid.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2saepwjxr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2apnftimr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkizjofa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxokjcf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xewwrmkc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnasuduj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnjjpns.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aajhvzdl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amxxxahs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iarnbgfj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rirpzvrt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwwblhf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxljdqi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfigtgd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nounphll.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slxahsaf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qujxczvu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umhfbkeo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tnncdgxw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcycetu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvanjbxe.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qihbrmiv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiemaoy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnwzevt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuaedrn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrdvabp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcrqfcb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vowrzerh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdvytzq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcimbou.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfvuukl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2segjndhm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cngelrhf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2grxegeus.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2devcaxoa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkxwdus.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtplfco.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dulexwnj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqjtyxp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kxostqmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2efukitda.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2headiiom.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efaatheq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxyuxjw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plnpdltt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2abggahau.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbovjhgv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrrrqqp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdbhxrv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2voppqmep.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shhjhzyr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2svkdmftz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtizlvg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggpqslg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qztyvgnh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uknroplj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiokryv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwadusv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2anuthgvs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhqmvkf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmfnffj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yisdsteg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjnime.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vicqmjka.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixlbvf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpihkxw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqyyzwh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gbatkbak.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjmjdsd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cycavkqq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiqrwug.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcparvgf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoydppi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2muzinyyw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpabqbrq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfunjya.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlvgykj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppceolk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wynlcykp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usxududf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kczyufvp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2urehelvf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2onmwytnw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzsjdkn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2okpuqcvs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwcqdqa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcinpmy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmevvk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2itydrajo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhdbxgs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gesedpbb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpyiozg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwsiaxr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pcifvlqn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2blevfilb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcbkjgf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtvfdhv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzjweba.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zggtfbku.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmphkhaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oijsjrni.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyxedcu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrfsgex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2feazpdra.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acldglpt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2arupccrf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkyuoer.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjybmfw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivatloc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2whgmljof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msqiqime.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzeaudg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxyogha.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxinzad.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2irswqtwr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqqyrgd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2inaxdvvp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2asqolduw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2chinhskx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjwraly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgshbyte.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2trgzsami.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcahyfl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2whhqtrsk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrwmhq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamyoaa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrbeohh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjzsndj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkaowzq.html


<!-- 参考信息 -->