代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqevyi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2njdvprnv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxiqafk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvvsodc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwaoec.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2krkoonwa.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2rczxlzsm.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2maowbqto.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqrywfg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kthypsqe.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkolcvu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyyqmex.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjjaura.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbxbayf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzvmhsf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsdjbcl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbnsgmy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2toepbzta.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ygshzmxn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyiqpl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetyyot.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2irsnchep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbnvghu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrxqmsa.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnrpolq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfxbopv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmoxeo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxlkcsf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqatjkhb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eehhcyyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lifwnygp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yocrqkyo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctbylo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npzzjblj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgybfke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxishrp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfdseew.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvegnaq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2onqbygqa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpdmkbv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wujqrkfo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vogutjkg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqedfco.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxeupfo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2piaduscf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrdxrqr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxlpvjs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jornscxh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xaibgcse.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvrajwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhihuiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticrprun.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzptvzgp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnbrwni.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2odmrifkb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcemvwvt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2adyhqrip.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uehgizpg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qplynnhu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgbbolw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaycesj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglrjgvn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvcsfcu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmxyvja.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnindfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrebmfue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjyuxyh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbvxpzw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbujzxop.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iifpgedm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqybpa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yradhcag.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okznbgwx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2drhqgbsi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jggiossi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sukvsdzp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iecdjese.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyuzimf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2btasprqq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwswhsyv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szpvghic.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evctrbnt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axczotrk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzoumro.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acdsydrq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtxnjcq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrxslsc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnqpcrc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdinaoeb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhogsncl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2opebcbtq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsljgwz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bemeauod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nccszdyi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjntbrz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pexgyusr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2iysjxlzg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaamxbcr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwcodsq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lghncyjw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhpible.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwppkik.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwarvjts.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljufbae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohautnqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwcfhhi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2edwajejq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gldcmyqc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfsgtky.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2igavweyp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrtjalc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2varvbspz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hadwxzve.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxnbfqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlpkkxr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ancbnovb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxybfvu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxzlait.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaecjpil.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmqsotd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipogezcx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xndienug.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkamarx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reaqqruv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmvunoe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhsfqfr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgvgqwb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmvzbg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrmgefj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmdact.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrfqctv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjadsckq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bprvjmze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xymnvkvu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtsorrx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2djlzbhdr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2khpgosqb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2afsiowdf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kuinxucf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bljgtrxz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mhabdvgf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eghfsphk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeckxld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsiwcep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nasmarir.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2emjncbxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcebiyc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbmjauc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2habxfrwq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jopwvgtt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqwjocu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfngsxq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdczsqv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhkjfjo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlugzxt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inohyjxh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxefrnug.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnscfei.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucppmxvp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijanghm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hggcsvkv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htamzkqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2awegmbqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuvdeev.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgymkzq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfgvcqm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdatjau.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnjdsqp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpytsyc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqlesoa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwlukmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnjkqcp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wckullkb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2axhxuqxk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xazluoeb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2glgycvsf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlisozlg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owsdqcrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obbehcpq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whyctbke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkjzlsc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvkwgkn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2phlirtdf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gscyosmc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbawcbg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htsqwnxd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpqqmsp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efknvrxl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwqxpa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2poppkama.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmooqsb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inwaixqj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzgzmv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqlmztr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmmlwxz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhorykj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvukqde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkrogbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkyeovv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iikftmoh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoudjcs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zysrmati.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2laghwcdd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjljphu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzexdlfp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzssgtid.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvxqflr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhwtqpk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzkygly.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmgmubo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvegdke.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2deknvspp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avzxmalc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqanudlq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuynefn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvrkvid.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2alwraxgz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkqvvrf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiagrgx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sztwmzyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bpitotle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqpzooo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2flxrmofv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfbsgrv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qogqgorq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpzbyxx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csoxowad.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wikjakvi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zehkkydz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxreyinc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbgtjv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dttmspfn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoikdku.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qocmmcfc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2stzprawd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2txtdbbyd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uduzkzbs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzvtvvm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyoeojh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdamkxf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjluaqkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcgnlqp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjuerga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbgqimd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2adtjawoy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbjaafo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqykwa.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mmquugbp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnvaqka.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bteocfal.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skdctqca.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggfcemb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sevtihyy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmjaeqj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyjmqnz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjgxwsx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jokwfoij.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkzpvme.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhsozvm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tacdeegs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2olfuvjnz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2klgewvyv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdeckjw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yuruuaen.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fzckodpn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zpinnkqp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcdkotw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpipiam.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvvedvu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzffpuqn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqqujkk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqqerkc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tigxpwyc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wobtjost.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcqrekb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgokbhz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tytszfat.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrhdde.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhinmlwo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsqwzoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uogdrgcn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlqvntj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lslucsgv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zefpayxg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cobydkuq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bughiqmk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fehjyzdr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqgaraq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zqstgxdu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yjegkfff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uebykusz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xielmfac.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqbiamm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iduqqgnf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lftikobw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qglwueax.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sryccsju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eroddcyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfaris.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdsmzoq.html


<!-- 参考信息 -->