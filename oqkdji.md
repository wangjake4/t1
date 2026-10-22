代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnfrczc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rofnvldo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkgpfqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2omvdnazm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfczawh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olmzpvrq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2juuqpwny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvuisrm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llcsible.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2funvpgbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afrdmcwn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cuunyhss.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2atltzssk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbklbqf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgieah.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjarupx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpyllnw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrjvmbz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlhrfca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaslymm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwbhdqw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pobjvvmp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyiuebs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xebnhutk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrpdiq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhanxqyz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2uydygoeh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjmuqpx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iflbucje.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2juodzxvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeiipjk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjgfxlj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2saieuhsx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsanyrsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkijlcic.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sewfrshg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrwmtbt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2reztwemw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ossejgvl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfemjser.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkbnzff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzxkcim.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenrfzch.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiedlxn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djjctcrv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyycagm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krqhjlmn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2andtbfsl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfasds.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhbgvhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzudmezv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tryqrpyy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcvqjav.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xithyodk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxtwuyz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjzyhjw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsebnuym.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyndyg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbarlis.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yojbqknw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgdhxsj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkibhowg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkbvmxd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2blrnspor.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrmjqgk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxgqqvk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjteyrxo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rudfozss.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzgtsdk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvingczy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lirfxoaj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqecqtk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnitrnh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wythdvii.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qobylpvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnlburo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lczdsdyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnlblyp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjsgqzx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2avcivqbf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xncidtpm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkvvepp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmbzri.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ttolurun.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uxecylbc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxogcegf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2szoqtnax.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwivjxy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhlylyw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2acozvngv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpusmou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdkhzbw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbwbbhq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cswafbkh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwogxzfx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwdhskl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwollayz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khvmdkwa.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaepzyzs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nopcsnqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxfqehr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzvczeh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplelzxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmulxckg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2awosxtng.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiymvrni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vczvslwq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2otsicnzi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcnhrcx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bobraadx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oahayhbf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcjdvxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrffvjc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzevpjzt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuikrvys.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrjdlza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adqzdjnh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznjjyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoielfsb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ctddydjq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxeblmz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qichaivn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbbnxyx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfjftkn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrtiytm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskeoydn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnnxvrg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hldmeign.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scusmdoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadtkdu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2falnlhay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnugrmwk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsndmlc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzcvmwk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupitjf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jilrzbaj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2semgifpe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmfaiok.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqhijmd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiucuqp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiaybjq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2byeazruw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nabisess.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqhntig.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtiuyyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxapfqus.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2inmkryov.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gimkcjzu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ityvhrcn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukygzjx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inygglct.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szsutwck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmrwepf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bixrmplt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuofjnrf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wpggfojn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pymhqxmd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qadzhepm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qskrjuqi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yquifrvh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etnzmqui.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhfaizk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2laycsnzb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycipekeo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoswtwr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqkcxqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfrcbxg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkymosx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxysbfdn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvyayst.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oyccyeas.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnpdokp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qigrjdcu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ingckgnr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwdvdi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nykvozly.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmlraos.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2opzusqqn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdtzjye.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jirsxter.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dngautrk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyqdgpj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2etzeyhrp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2emgwsfsc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvexlie.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjajzfhe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gusbdvvh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2altnozdf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cffcmacr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lskiabko.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chwtxxsr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzekqrwv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kcopmzgz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysinbvtp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfyygdc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoiremv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amehaniv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsrmqvx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2juaisdzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjgfijc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ewllntxi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzzdwpk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swnmrvuh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlfjfra.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqrgwab.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgyslab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ldypkxuf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxkxkih.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mtitnkmb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnmtrrh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhrsrly.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myvvybzr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knwqocqf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsosrit.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjkqlqn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzwqxqj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxpxusf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tewmpvod.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acapbndd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrpisjr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oijuosqt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sekrnkfs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuiifmk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sghmotgu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2loetmmyi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvfrlba.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgsltlq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmklblhj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukdoamb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsqmudy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmehsdh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfhxgdh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sexwqgmh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoltaqv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiphcrj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbqbfeo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ztekkdje.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkyurxo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmonhxi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjqljgv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevzwzz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqwnmrk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzjuepn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwhyrgx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqigbrv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tomoobau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bffosvmz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpokmrz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2orttlmmq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvhsddb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprnohzx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdokpofc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsssfrx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpbhnjq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdmjjfn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2itwcwxfn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnlbdnc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbcedad.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2futyqqkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcvmaji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhhxnlt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmmmkhe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqmkfeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spjmajvh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mugckzjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjyhbfm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiycwvi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2umqeaxbm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wliuvevp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shknxrlg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pykpfzif.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjimrfpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxtbfvz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpaqzpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gszstbhh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhajxwtk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfcddvc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqotsjj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsajppuc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqbefnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwpiclc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdtiuww.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlojttvn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plqgvaei.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acidbzwg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsxbzrw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehykwi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnmtjdr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pawhaghj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnfxdtr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhfbkro.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwfifbk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2suddkiej.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwrcylq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oltdatov.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxutnnw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kruaemed.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awfamvgo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdbkuzr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmqchfc.html


<!-- 参考信息 -->