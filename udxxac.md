代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cckugjkh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2djsxznoj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxcqgq.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uifzlicp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vufmrtqd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxvklnc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lqawaake.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lppsfqka.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kmriuswc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2stlcmtdw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlyllut.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnvmtow.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbugfjub.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxsfchu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgemspg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkgcorl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iibphddi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvulbhg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfxjrln.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksokgt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xppvtquw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoecnjfx.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjlarfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoriboxu.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnkovaq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqmmbhi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkdmkii.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2slqoedev.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2shzabyud.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cndarojt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2iugninit.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kskcboxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klkbeods.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzcqafx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ronmskvp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2curnpebr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nohmafau.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmbprfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnwjqay.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvicesgr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnayiqnu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsqhehk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukklvzhb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2typrkrlt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eathyazd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyoeqjf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwgjuzq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdiaiie.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2disndwic.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mebsuimf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdkazyj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqybzvjr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dophjnlq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbwuxr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iktnocko.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdqspyp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2urkufwez.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfmxjtp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwirxnz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsrhyot.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vedogyau.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdramgii.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddikujyz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zenupymh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfzqchp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2anejpbyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvabojl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdhdtbf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyowpxaq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaicvjj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enanimaq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjztsaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njyfwdex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uptkubwr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2viqsdepp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgptvoar.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoqsbwb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mapltcvc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qecznhzr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeciveah.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijsbkda.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcjfenz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pumhfsyy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gknodios.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2inzretop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaydbdbz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfakxttk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaacnor.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhkqcbs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oknlmpwv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbnwhrj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuwppzj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiofkrw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqnskrt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lspjeoxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zloakxmz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnvgdws.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szwuorqu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jowntjak.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiiklzm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sochhzpa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2idvvisir.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2myzazoeq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbilwkdd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcxjcge.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kszfifzl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvmgdqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whrxlxrv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdzuayy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tphezewj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnytkbrw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwelgihs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwrihgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuvtbcm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqldnl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsfszui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2donyudzz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixcrxlz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhrqfvo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sreptuwb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsqcyrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lljqgtov.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbfmhgl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvpuumi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyymxowq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2awuekkbd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbtepkf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xueikhks.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2etsuetmc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcdlywu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmyvdeg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2csmsuhwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokuyfxc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sjexblgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crclvehq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnsjvpw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuntzty.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxuhxso.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvektsw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjohctk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qafehsfk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzniwgwn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgopsqj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tswoniqm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wctlzyrm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqktudhq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2silrpmwd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiinndxf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jycqfmlf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tigmoixa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpctixb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azafghyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeivoezw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrovfpq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2visvvtcn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xogdgbzk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2houahuxs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwixavw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugbsydc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbvvyjy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoimaths.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hstorwex.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rodoyvlq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmukuav.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhelmbkw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwlgjhu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoatovx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdtyvyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtpihg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrfpjbl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoofoiz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2haolfxre.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvcjjat.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeohryz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfttwluz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsftotx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbzbgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeuoxli.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhijjcrw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiohxgb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2boigjctq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jezftzmn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpuudnu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaccriw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhjlnni.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqjqiru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oywgtanu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buigtrag.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbtjahi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdyedzp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwnoga.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpzaiau.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlyccao.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2utedyave.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2npvvilff.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeigxtj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhpjmwe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjtjxvr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2udkgvlka.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxeqepf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbhrayu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbuamna.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uywgrbwn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hksqxvax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkozmrq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojenje.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbjsuvn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxccqyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgezsxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mretoyhx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qtccnwxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjejrcjc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyrinny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iympfwzx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrskoak.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dksohsfw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2emfvaiue.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwywed.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwwlrit.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhcsiig.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2poeuvpiu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvoraau.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdhcclv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlakfpk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeuejvl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2syhpftko.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2phywxqje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlggzspp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgclohjw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvqmuvc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsarahmz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpoklvs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsuabxm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2folhuhtj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxlueb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tadklvxy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnnzddl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyvfxvz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svzaield.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuizpbcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjskkzec.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2excbwjqs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wootptbc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rddfwjbv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2asjdshpp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkdojis.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwexgvj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfmszfz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2badtziiq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eizyqfif.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskeszhd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkhndcz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qhixuwgg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhnedpi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2glejswdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uoponiuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnrcxxq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbtxtts.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvelgwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyiogkr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahholowh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2chtzmonp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqmdtel.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxxmjkn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxlgute.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwitfun.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoydpga.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhfbkth.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2druqnubw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qabxnfit.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wricmgsl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2eydnxlwn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwvvira.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pekvatkm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrulnqo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlinuvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuwfbsv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hquxvhav.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mbejbdzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdigazv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eexokbvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2javeofkk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2naydmexm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2esaerlno.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awowlkhp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzvjhlm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzrcipj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sboplmop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vbohacuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svruholz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xieggitu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkgfzgw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2abtkddxr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbssdtn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaecdnuu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msbelqrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpdyjig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ysewwfmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfetsbxd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exsurjyc.html


<!-- 参考信息 -->