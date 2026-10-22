代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjxrbym.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwypqbx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xagtpgwq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbknxrze.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pyankldg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwhpgxw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwrulsh.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tbketfkr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlqrknz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfsbidu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yehrvzfb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2natysfvn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwajpzc.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsreyph.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clxipcud.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rwagnmki.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyhbvlr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uptuwfan.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dylxrhhb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cckmrfuc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xscyumik.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjumryvt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2micggmjm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdijzku.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khkuedxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huersses.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzohmody.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2urxofgwg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnhuvph.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oetvoefe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2duvizwlg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjeobak.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwfczad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfllisfk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjxqmgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqzsdxk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhukupno.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztujyphx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlozjfo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfhoisn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcgpzdl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvghrbui.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oxktkuwx.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofchgxcm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogebhaxt.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srbesceo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nafdkquw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzxzoja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrfxwvb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psjvcmjq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkenjczg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqequjxx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqvgpge.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycxfwgt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbepgupt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjisushl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqbsgcm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiaroci.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2riuvzjom.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqrexpw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yicsjebk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeceamtt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwbolnm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxildoz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2betvaohd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlyalbs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2flmnyzms.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdksahyn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvbjkvl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yysnumnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2antmbljb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kknqutgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvbksc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2meynvjyw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevpvit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bshvmcoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqflsfd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjranai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgwbmrc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edbxxeta.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxrpzjr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sacshehe.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tloicnpi.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgigslyv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaqbmgg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqredol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbpmso.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avvojent.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclcmxh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciigepmd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2veptpoqk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxspixs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjxkhnj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpctdk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsizpqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2orfbenry.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcribhj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oomavhws.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2knadepgt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uiepyihc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynhoikt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqlgfvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dggjaafj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukknchit.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eugtwzpp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjkqvbi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbekzffx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxruwhz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2omwehxph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zffowskf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2htpqgdxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwpuafb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhttxdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldluweys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztycxacy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shanfdft.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jofvuhgs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvabjul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqpmxts.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnxgumy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jigwboii.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkzufzr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxaajfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtybxqr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijhibw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojvvrk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzomgoee.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sotthfju.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smaipsoy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfcvkgp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egbnhetz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxgkpsu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ynacbqwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimvfcpl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicqefty.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2arevsyrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxoseum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cipipmkm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2krugdweu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zktfptdx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pznzlqtk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qnplueei.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pddgasmg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eeauoscw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pggcqjzb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ashvaiom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzkwpjo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfwixq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lmklubhn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvqmfbd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeabulc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiiwuso.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heydvuvp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixngrznw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yftfjopn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrrwmba.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxqekue.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2glnjvsjh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2getfrxsz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egowgwjn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlktpkr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxklfwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vepacjey.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2quuxzurf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaydwkx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fefcswhe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkwqiue.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgknqzhg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqtakit.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdsngyg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvjdoob.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlojajh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmctcgny.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oaikpksp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwvvqqp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkwyww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvnitp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rghocvog.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvggchem.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwyjryz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfuxljs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhdkksb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2efljjtgf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2daalwudc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lntvissm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksefsuhl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjajqik.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdygiei.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atdibgrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oeskpsvx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xiblkgfy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmjatfy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmsljwl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcffdxd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiamjur.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayckfhqf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnwnmv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phfjxjpx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlresmh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bormiecr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcviwqrm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwtfxd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2avjyazlg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkinyie.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xahckcbl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfalrmme.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqbanbj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdwmwrm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzxekfd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilukmhfj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2stqjaegr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pccnrokh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxykju.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgjvciz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqhaivk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zddwsihd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmlyfun.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeujrxr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvqfmwa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jouizevt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjqnfsg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeagzhuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhfrajw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpickwt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkhntex.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2urbdmgyp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfdsjxq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkrehsc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhudakw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxosammm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2thjqappg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rawholtc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aobqxufi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsuketh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dfthepkc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjtjety.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxqxcys.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjkjghf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtpfrwd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obwdnihk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxywujy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntepputj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtryacsc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxqrzu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2muejnmhz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thwygipn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyfnpzv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qulaodhj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgjdhep.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfemuys.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanayjlp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhsvzmy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2upfobovf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjrbrpi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoqasdd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzabccg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjgzxu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoiqeuq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvdunvg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mdejehcp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2matjzjel.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qunidzao.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmibqpgx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2elaeejfu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lbylbrdm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bjliuaai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxibnhz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrveywqj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsmkytl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywrbyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vttyjhuf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ipetvqhb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2covnaclz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ahohudrn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzehqfhm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfomzyia.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjwufec.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gioszigj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2czucyaxn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixcehvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vcipmdbh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mywxfwcy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nkryygol.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwwgvhy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2okprewtu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpemexif.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvlgkxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyckfvov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwehcjz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjhnkjm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzukbpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bheljmtx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rxifkbxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frmusicf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2adajnpfs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxpiytj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meetfufu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deayahbe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vokjvokt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxdldgu.html


<!-- 参考信息 -->