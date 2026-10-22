代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjtplkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnwzuqk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2rocklkvr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdalcz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnqjhuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egcgnazl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2evtxdudu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvfzop.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipwmij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpwwatt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyizcvt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaqjyaf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sddcqgct.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkamuxz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nygiiqij.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbaljbu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvxkcle.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfwmsr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhisphc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flmwstev.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdrmoqx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpvzfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zydyqcpg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sptqczyy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdsnewq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiqxlgt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsrpdxu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mowbrfmk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnknoeq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2adgfuyjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwftzb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdomvdnl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2brqqwpwu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfrbcgo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnjuknt.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqaaayd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxokzzil.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ociyesjm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyftnkyj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwrbotz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmpdotw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvossfne.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobcqqp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxtcdyg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qidjkmst.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkjezmz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfhoff.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyubgka.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vatxcycp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqtexrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoivlyw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbdgkbp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfhonsv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpcymkf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzvlzwd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgamsqul.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwavlptw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqonebne.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqjrbmz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyldehg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeubbvva.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjqduaj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmgelsz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfecyjaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rciisbzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kytxnoqs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpxipqt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztblhzik.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgkfpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsovlyvi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjmsyhz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2owgrfbbn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrboakv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cugichsb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzvicru.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwurvqq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqdhnmm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikisal.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfqhhzm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkbsgxb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqxmjtc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyljtnng.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scxafctt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzzwun.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpncxmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkexrxbr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2esbfblkn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edmspvxw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoszvhg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpmqshn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2farmsbha.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqewpbwy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fitmwbon.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvssvx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcukbuh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqukkfe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvefudxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzksgpi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzthknko.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szezmneq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjelvti.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iradmqfd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfhmtly.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbcggmh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwliuaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvdtrvq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmpyrub.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2njdfpnyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhbqknu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpojwsc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2skdoacug.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmofpes.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eefobnss.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jhldkwfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfhkkkk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuwkyei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibevncoo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zjthzmyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbctfqt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gssqvkga.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gzephtat.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2admwtawm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqlgjoq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owvgyhvd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scgnbuwl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrgdbds.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzmymug.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzucsvbl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcglbrev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiedynu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rktsdxgf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umwwhaeq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2curvrwmn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiyhqxo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zulzrqpf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqxbvxo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzkzdvg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kutqigca.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zphrwctt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2idqvkwoz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2usixcqip.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkehpvb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaouqgp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpiobje.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eojeqehh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvxlqki.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yalqclkt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsvabrv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrjmem.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yytlumvm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idarjxdz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjerygm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgomknap.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpyspsi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2egwrjihs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfqhyhm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjqstgo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngowoivh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxceafs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goabzarl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttefuzti.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zxedqszx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etckbrmj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzqjimz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2btkodzkv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2emvhalnm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltburyzk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mattbluu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhqdsat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwdrvki.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwukhktu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvukoyh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2leiywpfn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lumijtsj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjjqidh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2itaehvpn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kalwaswr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zklyuqwa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgogwgg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oacqmygh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2thomcjyn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcglwpcs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rybcbzyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgqcenm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqadtrd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtchtem.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwwxmru.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpnderz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2moqpatyf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pasimtcx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzalmavl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxukvaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrkrgub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2logefito.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtdtokn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzlyjsx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoibuzm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrkjwkp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypokbwsz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpvboib.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmemkdm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcmwofz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oclnfapo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpavfig.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpsqcd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiwqzhi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ruplscoa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnzjlvw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsondou.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ygenjaxp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xmceiwdi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsontvb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwejekur.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wysouepa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqroxqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezyxiau.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxvrcrt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcxbpbn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbbwznk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoxolbg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkebcnvv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoqkuwu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkdmuv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofqdyrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbawzjtb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpolqneo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfernnw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btqkhasa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjbhymm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ruraxcey.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bstqwdpj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2evdbbkba.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjuiatx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyxpwsx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgwklnz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmjmjzb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zixfqdsw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jadsvoan.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsagrk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbphqlvb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nahvufcx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqibphqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2krlozgpw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wttxeppz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyewjsh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2woipvgev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxqzhqn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtosnrt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tltmgxom.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuawnpf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzhdnf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrggvwx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgdppkb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwqtslz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rfubvjls.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxpviti.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxnjpiy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcykmls.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqulajd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbcpjcx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsizern.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrtzwvv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nzstdetz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laqccais.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whcnxdqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brwgfxfx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtlqnfm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimgntoh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjvsnzl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoslsxrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohgnosl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdcqtl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dyonduie.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2maxfeosp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2baznrisy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnksrym.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdumzdiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwmyqdf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvzzooy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypviixli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2favkeeih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvocqqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbnqdlj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngdalme.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnbsdyk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkivormu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwckernd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2likhaizx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzywxta.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjbmbps.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjajdfoj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydydkxom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2npvsprij.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwoovvv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgelgnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfpomon.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfjgygc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emszbicb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdcykws.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpmbhsf.html


<!-- 参考信息 -->