代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcoxlif.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hucejrgb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjaioqw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plfsdgwj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgiuoae.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2scdqlahv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bozsuvdb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2smbwjikk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lysdultl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfelvjk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwenola.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oakcjeoj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlusldu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2bicyikyf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbmqywm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mohuysmd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2duybcisw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rngedrby.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jggpbkod.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdxtygv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjwjwxa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkntxtv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2buudouew.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gzakmuxk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjmehju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcpseyl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdiflqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzphfpll.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhjhoeu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxlhhm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqccgqhv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoioxxi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmoumvl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sottqhmq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2glpsxhzj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veikpxdz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbfmyke.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfontqyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdblvgsj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nshpqnmj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raocbstx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phzzoheu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyztfyiy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdcasxs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqhuipk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtdikum.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2apunsqve.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvfrkpy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmifgwl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgdbbil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2emjlmvsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2guhnvggp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknqcvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oinamoik.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzqzvgw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ficktiok.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyucdfp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2msehtetr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvugefcw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzecvhl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwscxmod.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnfrnrg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zefumoim.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxkvsni.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kiixanii.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2woudwboa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxgpct.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhkuvwf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdsxwk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooznpmvf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsnecwd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcicrt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfkwyse.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeggpmk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiimfqb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2edktjhvc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abmmqros.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsbpzol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyvfexu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrajiyl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbddupq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uotupucm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvipszm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnblhllu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvcvpmt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcayyei.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2raetqibg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrqytoc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuapxmkf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaytihm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqflqkmi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uoswbman.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxjixpt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxvvcth.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lejtbboh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkamumlr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffxerld.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvredqij.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhggntj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdyfyuh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrzymky.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shhvzfmg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcuoaac.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlybaic.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhuewew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwzhdsg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxypszk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtanjlqh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuykxlx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hllqhywi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaavysn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2muskndjl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgxzhvo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglrcgsp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlmlabi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nprxsmbx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egzgswvi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zurjwcqm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awsjmbxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnbdjsv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcpiuhr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiljyja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrzfoy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmrvati.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vumlybyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yobyqeeu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfywywps.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbxvizh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlbsxdy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhgvjse.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwfxtyc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nljdsaqv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqqedti.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jleckmpk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pthfvhnl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovnwaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyxfmkh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqzjrco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bagqxvvo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2acigzekj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwbszya.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrbxdwl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xubhdcko.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kasqjqpj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czzswecn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyfevuo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tuthuhpy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjqisyb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jojklsll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2etteczdv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiufcuxt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxrctl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvwtog.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvrqazt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2afoewuaa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rscgkppf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopkkyzl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpndjeb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovknhdvy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dswlelux.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuwvynk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsifpjlh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzzdhq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvvgrua.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2thggtbwi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoxqovn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpceyio.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdlbujc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnxiipo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfacykc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ageuomjq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqughihl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujsjbrz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwtjtmm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aefgjeel.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nusirjih.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tglyhjga.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwjkxna.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuxhxuh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emieebuh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bldgxgfu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhuzmba.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzefetgb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pomlhpcc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfccydb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifemnqdu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkufqujn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmapsxil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arosjfjf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zejpzgrr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxgcjmy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjhpsc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxhslfm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kayllqpf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlubqiq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nuulcigv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rycdxxoz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxcsweg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eocdawjj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jwywfqts.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pythtmbf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqeaxna.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kuthcufi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrdpwnc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezteyqbn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmargrhn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqenexg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcslqvk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nistmume.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2csjewvmw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aljwylbd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkjtdl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wpulbpno.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chatmqdo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2abpmskmz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkscmpyg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhsssuw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqomrjly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfhqpcg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygizlwui.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdlzuus.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rprqfvce.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kjerslnv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bphbgzjl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2acxnqame.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fzflohpk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2schpnsme.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hogozrux.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vljprxkr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qiufdgcn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvfnqcd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjvkzcm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnopctq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxynwaet.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxexnxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsgrkxn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrixpa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlhdztx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnpxhlf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkggywc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwoiaem.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpktlvvn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcxugkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxkyvel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwskyyul.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwikmbo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijelqjd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxpevyp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrgglfu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oluldecc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vinsifyt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hgycgzxp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jwozmric.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2npgblavo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eautpfzp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmetuipq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oatnwrej.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdelialk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnldvdk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mckfqvgl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcpwowl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygognpwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2efddmzqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvlwzxo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmfeymt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2niioxefq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjjsclz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuctgsx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2llghfclh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejgqrqq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjparcmk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxmmeuv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xpswrvyg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtimkbni.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrixkudf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoldabc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2eossmiyt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbhpoaz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzpvica.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxplnpag.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdksmju.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2crfikjsl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfktosr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eguwicey.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyyhcgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mygixyqy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uetdmvua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zevjojud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqlchpr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiiojzc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkgfteo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqfhahq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwvuxvg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcihfpif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yososfhh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2voyydchy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmiqktr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgmftvu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liaqkqoq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skuuirtx.html


<!-- 参考信息 -->