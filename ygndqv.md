代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iihzauwp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbupfiox.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aazitnrn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iprsobnb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxbfib.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhiluzm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sltbdnqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbpvsto.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tktonsta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ittuufkq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oohvrwng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mikcblvj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwxycro.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2meivglrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfyhdnn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cblesfeu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2acziwgsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmehmedp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgtumry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbfzjzr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reqptolo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjibdm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzffjzwg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2riafdfeu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2svxmsdcc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2amknxztm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgspvnh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqnmlry.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2msmudpbm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnijyeah.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2naojathl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keyikjmq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayioifje.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtqktpp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoztcqyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgitpxra.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbddwrhx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmryxbwb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2avbsdyyn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgiyhwy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jllsqgxt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnqosgn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2znggibsp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qluflvmb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiobrcou.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcntemb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mocgpinj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqfvnax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoivvhqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxkkjht.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkqynwo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhinfpeq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2psfjrory.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wopqaqmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxmpozo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lagdcjza.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ferzuikl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfzyldd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pymfyncb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epbrzhgx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjtjlry.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2abtimotk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakgkchg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkbevzj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjduhxd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjltdiok.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcywade.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbyugyh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdkowtz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evsoeums.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hndrrmxf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpnodvw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvpqxh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sndwncup.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyjudow.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wearmxmq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2edgfvbru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrmkqy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ucklkyon.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsfjxig.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdaybuk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuvoicv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjgzxit.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2orujchqi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrszplj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaddjbpl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xptclzhn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2caccvgls.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxurwp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlpipgt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2peysizxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslktdqn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmjljtq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2munlazsa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdndvak.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdgsupr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmxxaqw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqpsij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuedsxal.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zctfeeto.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzzmgka.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtanzti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unwcumvv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwonfpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmrtrse.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wamojroo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmjgeze.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iubxtnlg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmghucg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imhoedvr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xutmcyks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agjlavac.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyxrejr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcmotd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkxnnpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbrqgry.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rvopjbpo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxwwopm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iomoeund.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jppbvaxd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagormgl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tmygkyqq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mgciwnyx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2chpzaxrb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2knavsmux.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qitixmtg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vieexilz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2igqqrgtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaessyk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xckxhjil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csmogrnz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzmton.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2duzgjveo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npmchhmg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcbfeln.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhfdgki.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfenehd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuooiqc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2toenhjdd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gibuqzid.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrkvuk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vppeiyyc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmkgzqt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvssduoa.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arrdxhmp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwaqamv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctckkjb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzjlpun.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldnvko.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqdsahs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvzdgb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hohknmaq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhitarj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrzsytt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxxpjam.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaxohsy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjpfets.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvachcoj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ifldqvje.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmibfk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inmyeadz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqypbpvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeaqcpu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akcgprzk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsomrjy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpnnupv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtbtnc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pekigbkk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdvackx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcdrhes.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnpjtpo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwpqyww.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvninqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qhetzpyq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdazyquj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnckvyuu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgcafys.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjvcxxw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqlzygn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpcxzmp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqsmkjm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbzodrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2skkzlppj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxesoajt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnqxdhb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kodwugpd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2knmnnlpb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbzeoil.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lutyuhbz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrmdkon.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kashfevf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jhycvylm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dixubrus.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tennqfeu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxsmqhf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gevkpsnd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kelyurfb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiznsvh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcyxlqd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsiepl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqfhgux.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnwkhad.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsjibsx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oraxfxkj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2toxiqhfa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eslsnaii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2onvllhtm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxcjpwq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqdgbdn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaccwwi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etnooknf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowqrxtg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvbxzfe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnukdzuo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvzvozp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkmaoyf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fgglpank.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yafoxobq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wuafxoue.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2emdungzp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyujodq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xaamghlr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdijopq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdszqud.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpmtchz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnblcqxf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyurdhp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkidmxs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qvomkqij.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqewlhfu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvejkieb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdpafx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzqnhwc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnxaeh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpugfqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgflmtew.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qubiipwc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmrslof.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2okwdzsmu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfxqeoh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlymaoqt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgvkjbe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcbnxoa.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqntfzd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivilwfrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjpkvop.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2soyuvsle.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2srcahjnx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgrwuna.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dczrizki.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2maqbasdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfaizhd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wccudlre.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvvqaet.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zotnqzbq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kneqcbeh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvzesqj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntepswhm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqssyhj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbkdhoa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rllsppwe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2maimzucj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgzbirx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlrmhmb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxvhdzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpaoul.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjogzjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxyhfyd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2oceysdya.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2odnakvrw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgyygua.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbhibyb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnhtxcw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oorddgqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2krbysgmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhsooub.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlxakvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiiaces.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zoowyuhq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgoijan.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqwmtbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqysoqad.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duxvasmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yygzfbdd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrrngke.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otlepram.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2samdzekf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpaxujc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2awakllrz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyaivle.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejexikor.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwrogfz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfhiglc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2krmatgur.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwvftr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlmswfd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkztnpi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jixtvjbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdsrqrd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqlrswi.html


<!-- 参考信息 -->