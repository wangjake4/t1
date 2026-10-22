代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdhhkqw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htwoeruo.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbysshgi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlwtpnl.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayakisxg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2eeembtrr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsuawdj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsjnkpa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2skjksexu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlssfrxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dehggumd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xopiifjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2baepjhjg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjljnja.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeisuwn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2crjavbje.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmkzadl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsqvxsi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbcixrc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zuacnpde.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjldads.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxatfupk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrppqgv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qzypdxbh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cckhrbyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhujnru.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2biccboiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyodhdp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcahuuh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaranal.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcnxear.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbpdgyp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbdholo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bznsugbs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwlaqhz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkjrvps.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpantqz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfpdxiu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2badkarwr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obudrdae.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyenzcyu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbymyqy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvgewnh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacsvsq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2idevohag.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gehwgtkk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzkhavu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2erkikztn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iepxnmgz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdsphko.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeqhauj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bahcdbqa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2uccsospo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsnnclc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiweoqv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwjeatf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwtxpaz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2djznpgce.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkorfxii.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocikpsyz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdubcuea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbnkrdg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwwawx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpqagjy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2piqgntfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmozjzj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoygizx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuwbppp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvmasch.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtfqjda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjdezmr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjysvtjv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdlnqgm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iurhbduv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zempiymv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeluuvw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvhyzc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqudbzyw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iogltmdj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxyymdt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihifoexp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okrmikpr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzdhuph.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxmyeav.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgckuvcr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcxjji.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkelxwk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eccmbcyc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2seprqygt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkdnuwf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2spocbmkr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvdkero.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfhyyj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmfzgct.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xskdbnjm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtafooq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmloxaqo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkisqwv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nojeqqoh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmwzyti.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nusixdgb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lopcdshf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjttaph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeavbzm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkgktfz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbzqnjs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gglhaskq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmgtjjb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpwswww.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbuvcmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toahfqug.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2brondkso.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnfaxif.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaflxndu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dptkcpjv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sorvffss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rogloxox.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjdqjan.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjfvhoi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ophvdbhf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueimajoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khywgzmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tosjdnpv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2irggusnl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mosarskw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chtcwaab.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzewmrqk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2etoxaedq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2guqsjxsu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhvwxwg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tktryrlb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2arjguinv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2luphskvo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfbhvii.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyekvac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rfupyopz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gystcajo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ewczeleu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxhhmda.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2orqyzngr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcwgshf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awfdlssh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llrdmuit.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcnjdmi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uysogahn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgzqjfy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwddsma.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydplgqhx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpolqzd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcmvrqa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaivzrst.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztftnuch.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aljwtuft.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dytlrisd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvkfsal.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwgbfog.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmzfpmj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrqhhxw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbhqaeg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvkecjb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpswecu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxhjmtu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsnhpoj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbqdkzt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvqjqga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkixgm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ljynwdem.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwepiop.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dknyzybo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvjqpko.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlvvlzm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbluifg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyasnibc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2beetsyka.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjgjmrr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwonjol.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhjjhsy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpqualz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyvkflj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwqztkv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wakgdtod.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mapugfkv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvtwprt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeknbsbo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkwugav.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmyucpz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblbksvl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipccqfu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrovpqf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abzqyfog.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2krvztjvv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rimfjluf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvqpbav.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdjbxyd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dislkahd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvsvfhc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2arkjxtkl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mudkcfae.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2llubpmtq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2grwuuocq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qimbpygf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzzvuvu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeanuac.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsyecee.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vypghphm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvakcadm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbciypeg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvrnnss.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdydhmv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qupeflxs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxvsjiq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2htpvowec.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiavnty.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxczaxx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2eumeozct.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqjvami.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkyezwv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgqnxuh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlddrajt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipnlgy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vncjundw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oarkclrg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxuozly.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwsjaxv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtvahwb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qxinaola.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2stqgbvhq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvthxpr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2keohsefj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vwryyfci.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwgqryn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxczgbw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqxzpdm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sollysih.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdvvod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfdfpbs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sechyuuy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaghdyw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxolydjc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqyaowm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btfhosbo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luvqcflg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnsjyqm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcrfbdu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhishzc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvifkpc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2htpqcrps.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmjsnip.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdmjojy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2csxsiwub.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pxswtmyf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtlbzxm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jyscopes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2znzbohjy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjcpkhr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jncyvmdc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vskhtiow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2weqawtiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2amftsbsl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgslykb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpisrhej.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmbwekb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mypawdqq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uditocly.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkscbve.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjbgsnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfjqjve.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uapdblqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdzihng.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvimkiy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lboqtvpj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvfvkbo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgmoiuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jypbvreu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxsukcv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nixzfkzj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhxyad.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2toiikfov.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hucjkfap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddxjaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzoobtk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hupfnmqc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkqdtlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvtyquf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzosxqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvbmioc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2capajgru.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeudsff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzqpsjo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuomwzg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfleoggx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdmelc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2frusuywb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqwmqlg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbrudew.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dwavogdo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtmkiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbismxcm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxbesiv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiznekbq.html


<!-- 参考信息 -->