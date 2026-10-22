代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsrnhgc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqqgeue.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzdinee.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jccmrqsm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyxvluz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtjbvsk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wottwbkg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ealoflns.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiujihu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zupqlpgi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnamhsh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eoencvlr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2znzryadd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwheahhy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjmnkop.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftflcg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqyfrpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2devzjqja.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfnomzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvvnwnm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxfyxuf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmwkskj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wksetuff.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xedcxdic.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimnpnwj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcbxbff.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmhwhxd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaitdub.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhplumn.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlogcsg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rkblhbsc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeqakah.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzylpue.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tadrnadm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhtrpzc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhiheja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbekgegm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtykni.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2edyqqajn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxqwsq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vizxnzdo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmcwsj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgophjyh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oypkmwao.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinrhado.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lovrzhxl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmklhsv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfsvfgd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfzavrt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2txxatnug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxgjdth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiyueoz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteitllh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xisiikdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuiepua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbbhfws.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzsmktf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mziaatmu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyjahkg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klqkaset.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxywctc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2puklbdzt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyykueav.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkstlgr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoxrjbn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdsnzgx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvwkmd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxfwhjs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuwbrxb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uurhuopl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etsibuei.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaahcfz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiigooi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdyeafn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gluytqgz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxajcpcu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yivjyxsk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsngsbx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjpupbz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnvjwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeljguc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpmbdoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmcyblb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cooafrsl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2misnxonh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoswcym.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjjqrd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsihqvo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimyneom.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2otxehzkx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2igqxygxi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpovyjg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxkurwy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsfhmwm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfaczsh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdwhxae.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtwbipw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixitpqtd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeicrfpb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thmouilb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2usyinhma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kklgkfkq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxaegeh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtglkhuz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyhiclw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fykpvkuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2icrugfji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmgbhbx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzibrbm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsuprdb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2islgfaba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdlfpml.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwutkwlw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpemlku.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcoxhrn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btvuomvy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfwxdun.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnyuanb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsejajm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdfuvri.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfoqkcq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2morxyoae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2itobmklr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbliulz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2afjmiviy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwucbhg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmbqtov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxaqmiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyipdbwb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2akjsslbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adutnlzd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ravzvpuh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaxgswj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoakoee.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzicolmk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgefhirt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaskxvz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvvcfxv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2borhxqzr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tineylyc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jitbfrnd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpuwkyj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuibmwrr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yowriqnq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrwpulz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oojfmqiq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmetiwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjggwjtf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyhclzr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxsipjq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwksmux.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2puygjkcx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdvtxqp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvmffqb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygymcpry.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuahncw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpaggje.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2opgfkclt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjekfxj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2auptpidq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkttvjig.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtdqsdt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqxlpis.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdwrhnp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2glerbmsa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqiwosb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqvnqgd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtqtipx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnkxbes.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqslrym.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehlxri.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2advgtggw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiwlyjd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eufqozpj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcabevfx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdyqawf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cycoxlwx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nquoifjx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pklwfcwi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udcdtnpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zykgeruf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uorylnhm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kddfonjs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjusxeg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2suwlrlqb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2trtfmrzw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2diltfgbv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtsmpvq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2boxjgnpy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wanovhkd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmdvym.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxpbqgi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2inesnsup.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sakvyxbd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxcmlya.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qamijmmz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoijqjgp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqjnosp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glxkuces.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxwqzmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjepxpn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnclmlgy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmxwjwn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2deulaknh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xubnrytg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqawmnev.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaiqnji.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojtntyn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luoftxcm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzuarrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqauszjd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovguebpa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bpesstrn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkkwhlu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzauke.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigreue.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlwusqv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2comljcov.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cenozaqo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnqbltj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tszgbwyd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjmiaqf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sejcettr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybccdyf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcosxueq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guvcpqdj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czwiliql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqqpedi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2elhizmdu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjirktd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvqwgap.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yeggaawj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xptktqnl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxdngvv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkqelmh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrllbgqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrqsvbq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnehdfy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzbdaz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itswaxpc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2greauxfu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2idwjdull.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nppiqchz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlmcqfd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2npebyyci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dbneltcu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yffbcnvz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2opimhiht.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fxylnzgc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbfjbhs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzzfuyq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mijexcpk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmgsjv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpedtwhp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktthtfo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2umgullvp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyfnncd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2clwtuksk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrokzryl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krmvpczr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cyklogif.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fegvluyh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2umgzktgf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfebijje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbuwvgm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwohlebe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnvjrnd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfwmill.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixiosxr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2elxratyk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfqsyil.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlkayc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeuablx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhnlbep.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwnogns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dleqrpww.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2femiqccr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwkniuq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxwrcj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2orepzsch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgavyud.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwhleqd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjdxlii.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwihwjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiewval.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvzclpk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwuevuv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvtrvsq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gurjiayn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qylqlqvq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gawuzwro.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odrsufjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrntskj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2eftlmeiw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2getgtkqa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpxfqru.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlkkwyq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnzjsds.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxppgtyi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gstzoehb.html


<!-- 参考信息 -->