代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lpigqfnk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcjejal.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyqnnvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpcjymz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tugypssa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdhvlou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fmexpoxn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdgubxn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hweykkkk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzolxanm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeviibko.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ponkobxq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bscbhzvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zehomovn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuwlvhy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amsrmzcb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezppxbav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kehbviqh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2umjhrjoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzxybza.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spynuvei.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyqxzsj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aakubjwx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrkfahv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2quytedfo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpcjowt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2eulpupoi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnliemr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvbtvgx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfywzlr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2geasfxxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmxhqux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfshwqf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgxsupk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2redkxyrf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnlhyev.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2daulchmg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubnmggf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoklvrc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2siorltld.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhicbcny.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gchflspr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouofihqf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbsiase.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfnrhhf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmyiku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nczoumyb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyupltp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfttgznt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjnbnsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdrnvpw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2chnwwmma.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxahwrbe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmmpsm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sorjsovh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtdltus.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwzjdj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcqmvnz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgotob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdzuitn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbfufgh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ribrszqd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvgpzoy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnlsoye.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmcxlxe.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egdzkbnm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pasvaino.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aayujksq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrwhozq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtznalnt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzrqaig.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvqgigk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcbeasy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eblfsjuh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxydwewt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyclplro.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsfvgia.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dguprehr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iaggebuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlywxfmx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhnwbvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oysxmjgc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2imxgwayu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2stzmjcvz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2savdcpgo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwserggn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxlsepx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwepyb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hidztbim.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cduwqlop.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvcnlcv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkkugnc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoweptm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwvycu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wulfyoht.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lbacoglz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrouuwp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqbusri.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2axsbhsyp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfadijj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2opxxqfjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnumjrx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2seqhemuk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nttmaowj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npuioswm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczwgxa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqpuwvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxpcpwv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fupgocza.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeulsai.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhkjfnd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbpofil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbyctih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2legxbgyk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgkqvwo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxfkssy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoihkmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbndwvj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfkkjsz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2saecuvxb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrujuec.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wgibykdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiplsdv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkbpjnm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjnlwyp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnrjaxt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2botqlnba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2alndnwbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zopiddho.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bszsfopg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtwhdvu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qktmgnlo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2txnmfoho.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpxjprr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crdrbecr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgfabpc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saqzreol.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fulaholv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vljyhzlr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuhldyd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtxjyqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mtulofxa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meivevmn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwtqzgd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rayiuedt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpliuutw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpliplzd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfpgrqe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvnvatk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvhhuyo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckchkelh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2epfuewko.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpngswfl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2thfjxstj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzapdrd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2stvxbpkg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbspecq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2swgkzfmr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qepszkuo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gftefhik.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegublue.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsakmumj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klgbbfgz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqhbymp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkfhgtu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgxsiew.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2viujaexb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcobysi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgirixx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glojkwza.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dskzibbw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrzezwz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akuhipsv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xidptsng.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhjfnqr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmqksdw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdbmnhb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyitlzo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdxfpkg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzpgifh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbsbflu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnciqadp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoefefp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twnuxhwl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpempgpe.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtnglxa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxhijmk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsolcehj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzlxxfa.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgzrksx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smoeogpb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvbrhee.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vfteczju.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmrdgdv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqmyxzk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbcvotk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atmwuspn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqdrzie.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoywsomg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqdmkpu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2acqmyhpl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrlzsys.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urnhyizd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfegopeq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xsixeynr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elafwlqj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rusqbbkk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkjlsoo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzzwyfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2icnvhise.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdamgem.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuqgxkq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcnpbsy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjrhsbq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtjvdtg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixpbnm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oskbnnfs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjygbwn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvuzxdw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsfvkaa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyvpnzs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2godohrin.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mwowwrzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gonbwgcc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywktdqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnytqzg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdulazk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnleoaty.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhfyqpj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llulewgy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnvrcx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hopfkccn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqqbdvl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrojixbn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdmuzyl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxrjmoq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eudbyatc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chdygtdp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbidlzc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scoyksfu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmcdsjn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qrixhbpb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjvbqud.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2slvqimng.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vozugfwc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxtpvax.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2osyerjub.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2chxyrvjt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cmstateh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vrehdvrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwzovkd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwasmqev.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gprpachs.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlovhbtw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozedsdv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2djotdsxv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmpdpwa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sbplihoo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zaebqxkr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaaazfd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2edghqnqu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrjfckm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaclwng.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwceyxlr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2efyflwre.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdycqieg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfahgvjw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lupcbhfm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtvtfso.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsvbzrb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zspuhcxg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2irpthyxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgpnyau.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxbioru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nomjqoqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2advwkkvj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylshtxoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjznpqjm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lcutexsd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkuqitq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wurawhzt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fupntccy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jallbnfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxbuygp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbuduyu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osfxngoc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrxnqeb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hczzqscx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvipoilw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dznklyse.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epgtbwsf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqbtvzo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjffomq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pboljrff.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcludrsy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgzuyox.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpbbyun.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqigdly.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmgdtmf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2quevmsob.html


<!-- 参考信息 -->