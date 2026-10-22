代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2orwqkiqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoamcrw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2akoscfcb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cybbjghl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hincezkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvbvolt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mnksydos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bauyuyla.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgysswmi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xidsndas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhhbzmh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhrjwpn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wreufkfe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrcphuw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjtuylv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyyqokk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrkqlbi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phnwhjlp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tyowsynr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwoefra.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pauajdtk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzokcc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezxcglv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmefjazs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdheosx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tizuumuu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhwepoq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzskughc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzcbacy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2enpblmoa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcdajjf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2clxaiuza.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotplvyi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2diwpzhlb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xooalagc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tacsojqp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagekonc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshjpypz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcthbpz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvelwwpt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvarfkui.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrfgjfc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdzcavh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzarblh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pabnwbqh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcahquk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpptmdvf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acykvaqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kafyknom.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2numsnysd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qecyobfm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwjmflr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgmckuy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvboibcr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrmzsus.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhvglz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2orngiulv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kindfkqk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqdazk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiqqptx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxrtobm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlromupx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsbdwfp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfuiaox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fggccqbi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwuwdhd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vurdofba.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkrcuam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfeibib.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrqrxee.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2smuhsdpz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pyekwari.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2muacdhtq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrboyae.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwfhmng.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlceyif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfvpdte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrufpmw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbflpoyx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qythhxbd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwvcogn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woegtpia.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtherly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmebcv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cupljgpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkedihwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpnayng.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byaumipa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptoimm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrtapbj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gahdotai.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2btqfogss.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhceygb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oorvnllq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzppcdrr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvlmstk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opjlrlsc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kufoytbj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvzjglf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xarhryez.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgerxmh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcajapqi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tangipdn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2keubdbga.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tcchobin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsjafhs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjpmvsj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2czdjppua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoeuzbj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsbmwcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwefpqh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bomifqxp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhucprw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzwxjze.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzsalv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2utywhzsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adxzovzi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdmdzib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usryotaq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2efpuipjx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2euihrgkj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esjddhxj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olnlpevt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2segnogiq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoapqet.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2flslvjxy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spwmzkxt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhnpbl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnkrlwc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfchwyyj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axsjrisd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eamuzqli.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkxbigo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piaupjil.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfsoyrq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bultvkhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stutwtxz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oeadzlro.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfrqaam.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aijkhoov.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjqtjf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmasmmh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwvhmwj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbegdqi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zooqbobs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoyuzcc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmgyjxj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dlastwgn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwpocv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjevsyop.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xruykkdh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adwtbgkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydyefqr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkkduhq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygevgivy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xybnwwqn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bueipsos.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umqklkkj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzggyri.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcqmxjn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuuohwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2whtuhsql.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyzstva.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmfdinx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfajkye.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwwsdyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgcmwvh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxganzxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqfjbk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzaupdc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjqqayl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzgohqs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2laecoyfu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzatksgy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqvcwhx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxakmsv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2soohdulp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2orflsfhc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eqamnprx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrxyhgw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyiuxxr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdgsngf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jslvivrf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sopmqgce.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrxzgza.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysabsqod.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flarxafn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfdixgh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikscugwg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjjvieb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huqedeao.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2upvoayal.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rugzrxyb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiqvjwy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdqkxlu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csahyuin.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwamoxcs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbsxjsv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afjvvbvx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfuljod.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxlouyk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokexvao.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxsojnk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaoehpa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2grxjcoqe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2owgjcllj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2evqwulmm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wanxfwtu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxdfgwy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zjacribp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnbpsum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fetytuid.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqcmoro.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnqvthc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envbasud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jygcbwqt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwxbcpg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqtxxli.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmqrhun.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwciosqy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfuboy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fexzhtif.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqzkyvm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwoaxhe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhvdiwv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqraasy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpzacsr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2semdjrrj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvzoyw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaovkwh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrpetat.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zplnhjct.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnlbitd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwtstoj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2knytpvsq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcroryu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fvukitgr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvkycte.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljsksh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvoalme.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2feptiulr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yevxwyfh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyygsws.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzlwflr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2szvtsyny.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2clagmpjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iuledqiw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlokitqk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xdulktup.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabvupxc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuzhftq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2moiisvtl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bdduadov.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2augkxjbd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcyaosu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dezdqqva.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwnzyrj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlfymbi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rempbfam.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwngxrtc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zlznswmz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vudnpwyq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oaojwcxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxvqipb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdfwiwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2losqudrh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnyuwwu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajowqkgg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2leljjyue.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzubgxje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkefetrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsgavnl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgibaqk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dofhjfgd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiheldj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsyohhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmqtlvj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngaapog.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azpaikfa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugisgav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwzwzhf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlivkgk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzwjhg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasrqpnr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sbienfkc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrgwoo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeonhzt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mraqcqkm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtyzsbw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2usyycohb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnjfdlc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjtekyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsublbzo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2siyuoseg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqjhfuo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnysmyga.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etdruzhr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usyqsyiq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoaklri.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfkqwas.html


<!-- 参考信息 -->