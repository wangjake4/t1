代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ilabtxso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mturzoon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlyxxrh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lzosdtid.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyrihf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxovuukl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnitedsl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxewzyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ibozpjtr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgodcehn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dccmwhbw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbownpro.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2askpxbpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okofxdpd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rstqmhqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhvjusx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ousycosi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqwrdwb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omanxgvv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2pizcsxbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdquaxyg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvskitpz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvqklga.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ingxgjzg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkjjpaz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apdtusrx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjflxx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkorszxn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwhmdea.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdexkzya.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqnipgr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2plunyeiu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogmtlav.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fptyioli.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmavzlfj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojdnxqc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2stnjhirl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnmwibp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvksxmfr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldefqltc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiuqutv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjjgnwq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2drnjocut.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzubrcbe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfbtpkv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpogytzy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xykjtmnm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvuxgf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtuunta.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnadbuhf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uskeydtc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2efcfdlbm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qysblvrl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2esphhhry.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ampkjvem.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eksvussj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqdmibu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwqncaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2apwigfdb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujitfpgt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdirjpnw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpclayg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcbfwmc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhrrgew.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiujwtut.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaabxcr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmwgszv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzdbfsp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfmolz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjubuwg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brwuhtyo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugeuzjv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2srnbccbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nyplcsjo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeuoels.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcmsmow.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvehtfqb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2aivrrrqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2anypyfjn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwopwv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xipcxcgx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzeuyul.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2panxdtra.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qafpdrix.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiemrer.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vglsfdhq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iervmsmd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oertzdyj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuqjoht.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcosatp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjeczeq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sbssvlpe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufgsko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uryekneg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jplgyjvh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wigwwzzn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ninskfcw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2eiminrdl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyizboi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csxwpxph.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rczeqwbd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnomxxer.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmokdjvu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctflkas.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sinmqudg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqrmizx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkambjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2taiarvwj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sufztvja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnsascj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhitrhyc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmrjyqj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxtqdyr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxiunoa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaqcjhr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hflbwbad.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuewdnm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lslxaiir.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnmyykf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxoexy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvpogla.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xntxmrrf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2azmiylxw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2czapbhxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzlmfbh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2awazgkwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrvuvxv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtvhyod.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaukhou.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmbwpro.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elpzupom.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqjmtjv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqooims.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eviduakc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysatwibw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qipqsief.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzcqazf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2roxjliks.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jceotqrg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdihsoq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuirkhh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xapxohcr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzbgjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2seqqtubx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqhnkmy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnukqq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2idjjednd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2phsneery.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnprsrzq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwhsvbz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2itlgqbta.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnorpuj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfffapo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmnldhc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oexjfsdm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2toamcaro.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuozvso.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcsffct.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeckemi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgipthaf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukloxtta.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvuaqme.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2liwxltyz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbfgobt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ofphggke.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jilmzbtl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeojxud.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwucmozo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqxoypc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqxhngg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blsiarti.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdadcdth.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzyxmzt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemnbkk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvqhow.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoraayzv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyosfdf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufabtmvd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2befclxxp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apxamnvg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcviqga.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2apkbtmjh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtzaqoj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvregue.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2czeuyikn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyxpmfy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bryrujqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrntrv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlroqeq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxiuxz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcjskax.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsclgwy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpbjcel.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fteggdsm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhcqwct.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwulref.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2csyalrqn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuboefb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auvolmol.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zptwavdp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qftpknzy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfxvtsb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbeozqf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taubqdhw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yratwgvl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnnovxt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkyyait.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrrjasp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2awguyvel.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxexkzs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvlmvqc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hximnbas.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yovexgkt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xppskhpl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bestqaac.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gacqifea.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhymeci.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tltswpdd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdwdhid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqendlan.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjovugjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcvvjue.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyxbzhl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sepglwep.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjftamf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhkggfg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2olcgxlll.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrrevqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjchartu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllwktj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgezysa.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeuuzqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdxiawv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnwomdj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrmezon.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfoxrpi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgsrfbq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tewotgbl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkqsdjg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjskgafm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpflerms.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcrcnnj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzhmutu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfwxqgx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqrqyvq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gayybfsj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvrnxbn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2drplohpw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yyouxmoz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfbaafi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pomojooe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjeyiwu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdvbtbc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwsfngt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chazbuox.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmjflvw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyyygvr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kormmsnw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzqmqax.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtwjrc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2eylugumw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2auemjuah.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2suuuuqat.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvloavg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbikxlu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbxyxjy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxiwagz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2segunyxw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoxshfd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaglubc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2clmzvyjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuguymgw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uitdkivb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfuzlwv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2inujlbyz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcxvvbp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyfzhls.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooujwhns.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoibugam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlasthm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eopimvba.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrceaswx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzjubie.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrgbsbn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zznuffki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaenznjp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhcmnco.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylmdxbt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhbpzuz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdhsjdt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oukmdmcg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcikfwi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jwakxsql.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxarhrll.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrdpxry.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeytyrb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuquglps.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kagaotgg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvhtssa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwvsiqb.html


<!-- 参考信息 -->