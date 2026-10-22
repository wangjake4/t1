代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubamvwkn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgxzqyj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uupujths.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxstoi.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2enrxgrld.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfveaad.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpljahn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aixjysxn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2thdguvgh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvujxhw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmhtjhr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbchqig.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdjwske.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2iebdipfy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkabbqdl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkclnxy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzlzvpf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycutgavk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2favetbcr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvxoyhe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yihtqmde.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2huzbwhoa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmkpxjx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqmasir.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xugyrdkc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osbbmuac.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqihmhme.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2krluyoav.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzkudul.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xidsubpb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufopandg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqutkvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylckxxyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiljqyy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yeprmgch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpchyzb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsypoukw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2iexvokmz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klcunbma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdssrvk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbchbmet.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeimyja.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2otlcscop.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyxgafk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpatocay.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfseaaaj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvrjkpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfobhtu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlqwokm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrrdwm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2clnijhbx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sapbqhwa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggjdbkl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwebvga.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2szkrqbwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgapei.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wumlwvle.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuswugs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vceyrzkq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmtbdaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2felglzfz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2npzwfesy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2esesltbr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yykrwqfj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbccjvh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrngahn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvdpwlf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgkbdm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqohcgb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2whrcueya.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cucofgrg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymylpyyb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqbfikl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2slniuevf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgytxgfk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspwvod.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckijgvct.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2szqgbwlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2psmryaoy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhkvplf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvkixky.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udnxfmgr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psykkqti.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iexrilzy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyunerny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ircgyvtw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2docwdvdv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlibxhis.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwrkrih.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmkpfau.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwjnzyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnghgabd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcttgkdr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnjttgj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqaxmi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkevevqh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjphcrri.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfbhkpm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiqfbnl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tgchczwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoluziv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkduswez.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgwkvzy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sddmycwh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxlibdi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbavkvor.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgpypom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhoogat.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwgqykt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpwtfpc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxckdgt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsggygc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2imhuglls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdsdhpa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvojpsdw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fixpkpte.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzyatxn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2eharpqkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdljikws.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ficlhqzl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkgnfkg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkppnjiv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxssnpa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjdvil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhmjkhx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnzxmlz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtdozz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qokzuixa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fobshrnr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsprpoip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgtjcyv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnjhasa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2btzcwtfl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfuflmf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eytiwdgi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkcgckx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhjroyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2clgajiwt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hntpdbzx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2azfnilcs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfzpzwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvffjfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2donxkhkc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mnprcoyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldefhpzt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2abcbbioe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jelajell.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2juzvgspj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zkntvakz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsgzuri.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbrmzej.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxhotcp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifilmsun.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezpvoqz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxaqwow.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hddiokyw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avkujrop.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvoogrm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhkkgyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtpjbrn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziakyiak.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnnhbge.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgeozjr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxractjh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdycxln.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2esrblayp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2irjdvkic.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kybxfohs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnievrhn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtjwvae.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oldzcgnx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdyctel.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrkwaaw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyfvatt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyylklb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pemijuuj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuaezwj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkekfrs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpbismq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqnwpmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cweosslv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oomfcpif.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwafslz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rqisgxrc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2feqcbwlm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlrerxi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjqebnb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atchqpdb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaxerwe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgojkdl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blysgmdo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reewqwpb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bdewapqr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfwhxva.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmimbcr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhahyoia.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvwsjiw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhozeyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nimltjku.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrckrgi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsivxcjp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wtynspeg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sftieerv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjbylni.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgokyhmu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjytrga.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvacfxyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2okskcniz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcypsrl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlvxpmu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbhivqh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2molwuqbt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgllisw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgienmu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kalayfzg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyftodg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vffwkfqi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiqjtdh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcrvdev.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2arstehim.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrgkhlt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnuqsxn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2llsolczs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpfyhlh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgoysgz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgzsxoj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgttvmo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mishvgnz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdrtrly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiolprw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnqscqu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nsflmbcf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2griatvvq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkfxbxc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxefzko.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnuuhlk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbmclqd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zzufgfsn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbbujus.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbddkrox.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwxymzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrlslxs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgumbphz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkuzdjo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqafuny.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxryazv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpclmmuc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsftlli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsinppq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctzrhw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdnmemx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2celvryec.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yalczqwo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsmrswc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mleukamj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvhcpwb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxnzyn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2frfjuxyg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbdqngq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhihxb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzhmkmh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyevclc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysvioxr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yihzhlxj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpwnqn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvinqswd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2avoihhlt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbaeshx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kehoblvi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcpnqug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkiwdv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgclfew.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwngjkd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rovscesr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odfeedrz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmgwox.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcmfsxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkkcpws.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbhqfjp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnigueyl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hugwqmuf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2difpxcav.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwryuxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpfpzyt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kztecqzo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pignetvn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nziegcch.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkitkem.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvirvlh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsnqxhz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxnftwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjbdsud.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtmaabo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywosyeda.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2labfqsqw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nspmvsfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avehytso.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdfmmvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknpgidv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsflooie.html


<!-- 参考信息 -->