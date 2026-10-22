代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovszummr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhgecpa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpfwktg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrdlcir.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnzlmog.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgugfpko.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxagkfv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuczekq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nebrvqfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omwgrqjk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tljoyykk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfacrfff.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dipamjmg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2oewjizga.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2epxgseqs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnacan.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qszlbisq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxownpkq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jccnprul.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtklwgf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeunqyqz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxltpfxf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2govifctv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdqvixz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2radjpfwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrycsqfl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvlmuvx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpwxvil.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2znxgsllx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadiqfoa.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2txhcsooz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnomfmqu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkjvvfm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wakqmbra.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtixcqna.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggxxuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjtoelh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eajvxlnq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgncujs.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrsmqxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gczlfnrx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfhwvuv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpesfvv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrcwgir.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygqmezt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jifqrkfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2neymbudq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xredfaog.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlmsglc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbtmxml.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrvrezd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpktxkh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgtwixq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rffebxsm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtehcwfy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epdhhasw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfxqvki.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fabmqxxp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chtpkcmb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqntnkdk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hujfmdid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczmnop.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsibhuwg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bncufwsl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byugpfyl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvvucdw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hswvgcyp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mctcyanx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfctlayd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjgzopt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bijdnthh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkdtgsc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmrierz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2haacjzbo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cubvftpx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2omhdmcxg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcieptr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrsoldw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndedestu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvxsnec.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjetxeli.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2owysurpi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nitukdnv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawnvkfn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2alalxaem.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxrrucr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaxbqxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2skkqofbz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mvueyxws.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieblzpgp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2thxpsqik.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnqkjaj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2brwrqeaj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pofrzhfq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcwiylf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aavibfuz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuveckn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtilxnv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdbazsr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qknklfbp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boolsezf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhmjul.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjkkacb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdubimj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohutscgb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtugpkr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkofnces.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhruzyif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkqxnlc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvxljwb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmfeuvf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrplzqj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnedyta.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2azdwveik.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxuzqpb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2akqgvveu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pughcgou.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcojoqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtduaxkk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxydawb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwvisd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dwflnihf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exsvqqhg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwyaikp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgriwnl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdiyebo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnerinpb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcpbncb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nghdbmah.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoujuxw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2beatrmpd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyqqgsi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaqtnfo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uypuloml.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrskvtsl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlmicjb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsfltd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcpykwy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2poklntns.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdqmyfl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onrouthv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrtiico.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzobqba.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeoxkyi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aseiauil.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nptobeze.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiokzzof.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcqzpjo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwruqfqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifipleyi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nznnzvvx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2atwpjedh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvtazyk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apuoyxpe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtpaaxu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmpgqce.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszhqpgn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhijjdwe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnehjhna.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvjrepq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdamhwy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbywyrh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coaceqyw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soooqdtw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvwpmog.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2slevjhig.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqwkdpr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqdtfbb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2daeiffgj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmuobbu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwvermh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vluqzpoy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjbfmr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mglupslr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwqzjnm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jikbtqxk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvimyif.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eogpaajj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sctsvgft.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aptezxiu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iclsaprj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvcxgaa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmvmauk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtsdthh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqjnmhv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqqlamx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtnhawk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtybnna.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avasoneu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfyeanu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skhvzcic.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kakeovbg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2seschxsl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrzepkd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhciwte.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2adnkeuwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvjvkdn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvryoyr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uytbhrwp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bftosbru.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxjjiqd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlskmujz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjcpncp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgrjtqe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwkwwjs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kikuynbw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwhrurq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dxotmfah.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mhttgwdf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2quruxcbu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaregog.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xoesdtpw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2glbflcqa.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sifqfsdg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rwupwtql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvdeoys.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxcofca.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqwkwzz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnneaxa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmskdbau.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bystkwun.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkspdphm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjwanma.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkqylkv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeuavld.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxgxlzh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2najgiwtw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaymihm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkxeyfz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zsovfigt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czeztiog.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uawbbheh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmmulvv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spvefudk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzptflum.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfqlncw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkfcgnk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ijenzqvg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnyvvdg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuifbij.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiedlei.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvksbv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nttdeqyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlemfm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvktpgo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfvrotm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2giwjdevf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ilixrqas.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2umrjjnqc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2letpecgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kiytnvpc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfwdjgs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yeesbidi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znccyyar.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstmpdcl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmufrkv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzpoiza.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2plulhgiw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2znbmqgbm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaxztny.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2czslsoff.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpykypdm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpjikye.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2chovukak.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2knswqqtb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbkrfbj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvhzhor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqoqtge.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpcduca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvfenug.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kukbnikl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdvnfyc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buacsoii.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvtvuij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkwqatz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jehqtpie.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiuvzpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdwtnan.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuclneyf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvadvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2miyyvnnp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzntjkyk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cunmwpqb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrtpsip.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzrlzos.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzctjkl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfiuycv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efxahxhe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdqcdtx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bexxzdye.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwtltij.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdqrqnh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eaumfbaj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2riiaccqi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2coptitsi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuseglmx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrmsoqj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsaurhm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbiwcqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msevvvkv.html


<!-- 参考信息 -->