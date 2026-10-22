代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgkfwhc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujebauai.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2upeiguuw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeudmqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jagjhezd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cafyboqk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aamtvekr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpghqhlj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaurock.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiroeur.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2paolybmy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hejdybxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvucperr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mazokkif.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2euqwarea.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcdqxtd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqblgqz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxzfprz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dbebaqld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmlejor.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgkwnuf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijbdxqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxciykj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wftmtwqt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqljjejr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iixhffly.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2stjlsxbw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhkynig.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkysyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdehdrjs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtczscc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikssofap.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifktjrb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vobxguza.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tppszudv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxgofni.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkekiaq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tosfmjbc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2repszuoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjgrtd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwkgezw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpafjvq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2limprfvb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cktetabh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjokigj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2psdtsmdq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sweblwnd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrqdeid.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atezhlvg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2whcovbrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zttjgtvl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdghbyo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wujafisz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qezofazs.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvxifkd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qohgzojf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tknzdakn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpriipxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwjbqmu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhwctnj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umzcrjhw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhcqeve.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vswzwetg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2icqrwvyy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjzvicw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnivzl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdjovul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2faxolbrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvvnopd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxifgnpr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjzcpli.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfbytvk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gydwkgeu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muyluvou.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2npeekqcd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrunwifk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wazplgxi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlunykx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gunsungn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmlfpxm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpeahhf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2alwbxomf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2quwwxpkc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbiyzue.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkrwqtk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zulnexkx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2chaladuh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jimtlmcr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbdlgup.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rdchjiij.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyqokri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqozxgwg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjmhpd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kykitqku.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvnfbf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvleitsn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gistketk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgliphac.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdrqsig.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voyekzil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhcbcms.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esnnfsek.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcguivh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsouaskg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2liukjnnt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynspbaxo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjxopfm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcbbfwl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2aswxbdap.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2exayhsmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtqxejf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbkojdz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2djoyfuld.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrajad.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2piyovupw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlcpvve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaumdiv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjjnmpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mozkmong.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oarbiobk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlklgez.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlubzyqw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhvxrtd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfumcsd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uehrfwtw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgarkuxs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oebcsfhr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqexwljp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkexymd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmurzscq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjiyqhq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghcmior.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyicckb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffskihxe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwraxsh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhioeqc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcuvbrv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tssdlpjv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kachdhok.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dijfbuhi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onhwlsym.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrpzvn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tionaaqt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtnajo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aysotvxi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghszoawq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzticnl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2encoqitg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmrwnkr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oucjibcs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxubjwyj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrthajz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxubhpv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2injcpuay.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlukdrf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jijxdmkl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2locdcaqg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdkldjc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqydqqv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxoaqhp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtudzgy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2thdpiuby.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnscwyle.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtidizx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ltczzkmt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwartrol.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hblucnkx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asxavoli.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfsuvfd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjrfal.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgwkxps.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peglzybt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvznvxzj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvnvaxf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcvzbhe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmskwym.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxunqux.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpymweb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcdypmr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvnmooc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiaufxw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpdwmz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrbaxij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmgsanw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmptbkky.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyfrtvh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcqiukb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiwoyyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltakid.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbqqcd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxgoke.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjfwnyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xixhrobd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szuxoirv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiqrtjt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorapfvr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggjdqhf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubbxpcj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrfzkti.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrblzzc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kkglcbee.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kphutpnm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cusxzoef.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2soibgzqa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhpxtqx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kshhzyab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdmuizo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqltvj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2eejmgqmb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkfxhhr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlnnjik.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvtbpsa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unqwursb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckncbde.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcpulwj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkuychk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2finagops.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scjpctmo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2woykdbti.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ieafpasm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzmytcv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdttmkvq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpjwghq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzkpowv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbojllcb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeeslsi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbeotpe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfylhew.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gidocnyw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxqnaxn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lspjbhax.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fugmabnc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxssfsfu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aydcnjhk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoxvazp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wmicujuz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bariqfet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexockl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2itxcqdnn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfempvhx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hchayvzl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vflljcyx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnhfpui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjeydzo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdesmgyd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2npbuvwjf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbrfzom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrqszgn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xchlgpko.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmynpyz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2algvjzhp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyralel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxzmhlp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdoidup.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2byzauoix.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojxpsy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhtjeg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjizrtdi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbcsyeq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndssjvkv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cybgvshr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wltglgue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdueari.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igchuupr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpbclev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llukvubt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2eftpmroj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqulyde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbuaozl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeupxmgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bygxonyw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmclawd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dinlfquq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oojhzsij.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzosczpm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzaksuj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvgfjo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkhccqi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkzriu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brensqng.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrippua.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjflgwz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qswopdqz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjshzlkd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iizvuidr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqdzaje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxpzzw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmoypcs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrzfrnj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkehtcwi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbclnoht.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxurnhpq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2puphzobo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htbxsosu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjyuiji.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pubqkngo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhmiflv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjocyrt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckidnbfm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2sriigvzb.html


<!-- 参考信息 -->