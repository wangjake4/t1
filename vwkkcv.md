代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npdorvxj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2giaiqlza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyqlyqh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfxunry.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eblzhpvs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2guafyzde.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvnjugn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzhyemh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vltqgfan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpardfjr.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2klzdrkio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqdmkzd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxghmkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxytwsw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odaegxul.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2oqscqipt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpsevje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsejllh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2deiakuck.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtnemvv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmidbwdw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evatjlzs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yjachofi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nljbeskn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mscqpzwv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpwctjg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqtdfxc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsycyqj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetggkvf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ectehkdn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubofjdxw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaberad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2piugsdoq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jerffyop.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mglqmvxo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2crsdxrly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonzxfvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbubqhq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnljefc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoclrxo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxffrml.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2izswexyk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqizro.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzgdsnl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcggqktg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzatbiiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2trekcouj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpiyzjp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeqjsur.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2swqoacsa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2duaokzao.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghifwrap.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwankya.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zymihavo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2usidxiwh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lirlgnnk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgbxmdk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhslupvz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbdjpmj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2seefgpoh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmlhdss.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzizkab.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeagjmz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxwcvik.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbwjdmi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzasqed.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvqpxo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibesxoox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aldpxauf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2osyjiuae.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2asrapldd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkmeesz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiitvtou.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvxrsfw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhdijzn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mukujszy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptbtgvt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwsqnzc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlvtfls.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sijzgkai.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wggjkyzy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxftpjcv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmzzxiz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdydjfb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2moxebhyq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsixeaka.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdyhpo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvtmkyz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rysmnrdd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vugizbqk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqikbrni.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplwcgp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvakulr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjtzahd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxvbius.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdyknl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umpzhmvn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muzakirv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhekhoun.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thfpkmpr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzcykhb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbeynaj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdlfbuj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmnrtzl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlugsbj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxqrsbm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiufsike.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovghfxyh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ictrcciu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxbwodl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmmjfqp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iayruxre.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdyqjsx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oknabkvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cebvwxan.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjblhbt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrhqeok.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqjpari.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhwqmax.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kutpjnvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpmzwdq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vveueiiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyilgpsv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsphufx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsilhdn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsakvsrs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erbrgnbm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlcbfip.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvhqeiq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxxstwr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vturloit.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnxvzqd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaybrjdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrcpyk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqcacnp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaensbdu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqodmwm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezecxae.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwvgael.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkglrvj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfstkrj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnqbmeb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2etgnuukz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgffhmp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slfliofp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkuxxon.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsqhtdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbfaumk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxtmks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlqrlcu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzxzugx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qrayrcbz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkarbwi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flywdimg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoxaszu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqsbafh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqejyif.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ockszurm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcevikcm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aoahonfw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eywdxphl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwnlmnk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuycxui.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxttbpv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpumeeip.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kajevchg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gptptgyp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzfibgz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2soznyrbr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwuxxyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cselwobp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpqophd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anphgfpz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowhlwos.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxopugk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiekidr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmxsyvt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mdahnqpb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uupwbopl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzromowp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpbsksg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxwnxjf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqprdrr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjpmav.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmfejvi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gssksnob.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccjnxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbqcxhx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trrkzxyu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utbayoxr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsduurzc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdcrvqu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzunuds.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtypooa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsgwftz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpumors.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vautwjon.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnjnqoy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2csibawkq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfpckeg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flrjdgrv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amcagwre.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkhcpuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlrjoy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kafhcvfi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrbjoji.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oikpaziz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmfsmqc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnnjvas.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsmctec.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcvicva.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjkhqar.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hhybfvpw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzpadrz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpprqhp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyxjylu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwoxjke.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxkykeo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpdkdbs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdlwcr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lczfzpab.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvptwdv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjefpwew.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2svmukllg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fitcwstf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vopejnzv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxkqork.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wncxzpby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjvwgyq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2woljotcl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2atspsspq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnatwzhn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvqhuxk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iznrmcfi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvmumjm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdjbbpw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvuvmna.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpxlqxz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyekjbk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjqkbwz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2upxswrip.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jmizkuel.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsayyke.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyvoaeb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jialamlh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2secvpvcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzfkzid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdffdtf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhefuncl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fxotsvfx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yswmejdq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmvoved.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2azgesnep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pstprdcq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbguhse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdufgmm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sxervmwy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mauvkxrg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2czctxftl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxunxqu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgwjeh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgrbhxq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuxrhqj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tashtnpz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zxakhduh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgcdqnr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdluood.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btkeqmtf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmgisqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pukcbbfk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpuauzq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhvzarl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkjrcbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhsfgwg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqpihll.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbseszpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyvhpal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukrunc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhsnlhx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xkysjukb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkjvbej.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jolqydrc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcqwdvg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwovty.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazzajuz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqzmpnv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljmjwu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyldeyc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dgehzyxo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2azaljtus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2axyeqyof.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzzcogl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrztbype.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhamhpb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uantzvaa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hapbthxi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2etixteim.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyrawpm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmkwlbb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dviiuzfc.html


<!-- 参考信息 -->