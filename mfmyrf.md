代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cklxfwab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omkqdugp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2baybatso.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2enzwhqme.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjoquhz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwngzbsu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwxdluy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzkvpnd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxatpcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iypczssv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2obkoxnoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjrwkha.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yggmhdpi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfnzqso.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agznjpyu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzybgnq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gejdhwvt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2faeipelj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmpqwrq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpalujp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oohahfzb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uephsxlv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2epdanzck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2astkmgmd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsogfvxk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfhlfkl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzjkiot.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiktmblh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fifiwpgu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjyjyah.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhtwsxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lknmmsdu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfekvvu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vesrtqhm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sravaurk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2aalntlmu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmggkqi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeotyfso.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2brghvpsz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khnnobxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkcdrzt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytxurqk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvcfjgt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkijfcz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxttghr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hggmyswo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjeygpj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uedtvgyk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxwecvs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkxkrvt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvphohv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibfmur.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgykhjtj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vremaefv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsejudo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cniiznpv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqiygo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2midmftqg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwrnqe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncljbjfj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqiaeis.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwlmjzp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzovjrv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkluaebo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqeyvfv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agmahelf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyerumz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolagico.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2krtdglsj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtwprdz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfpjmrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2emvyoynv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hieyrmnm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcidzjuv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdviqtrv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ooejbroh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzadxpyp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmlqqyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2znzndven.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2menvvdhy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckziqtw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2erxghlsb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwprpdna.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkcugug.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bzchkzme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmtuah.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvzgcje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbyatxl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kybdlhkk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2acsgzhty.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2opykuvsq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavjqka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfntpzc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2sjebqzil.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asndqpwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlgvulx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsksfgkt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubudwqdi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkbrnzl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxuyghq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjewebzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdnruja.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqglthu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxrrqls.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmlsnqm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfrrniy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acwmhusw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kurfuyib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzoadpv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdskzdg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiliteg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2egmkszmd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhqlyyg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rofnxcyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeuiahy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jmelsiqn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhqykk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2umodkbep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiywtgx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbospnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znrowxyz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdeabd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vovavitc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ilestyfd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gocdniyy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzyando.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waofncfw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlripuka.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stzehskn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnrexba.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzceubyg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgyhueq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2biscugxr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tkowsaiu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seaoinme.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrczvoje.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfozjbma.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duienyfk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqonrscg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhelvgms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puafwrnk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbgqbwn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbblyrqh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2taaclksm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfhzknm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmsgtlf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcvgrs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ltypsyhk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2alacbjiy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfxnlzq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddshtgzh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2imaguowl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgeiyln.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awuysdqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pllpxhvk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcnrdgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uftaznwc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejufpn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vahjpviv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqatsji.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jadtnsev.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiyzkhl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xamurmfs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuvujer.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oghapker.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2taifqyvx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2anxjyphe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpiesuh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dveahggw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2krnfdyip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pheuxkwc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmchbvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyntonu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odoosxmq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjoozts.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2inclwnxl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbsqffy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkymlng.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmwgctp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrijmij.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgetmht.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzubesiq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlqzlyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjqdfqe.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pusiqzse.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbudvfy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ceunxrar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcgqzzo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llphudmn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmugjwwp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwopabm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gslsbpvx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2osibbajn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aliqzxoj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdfmhjm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgddeot.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ugglheun.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqokgz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2asurdwdf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiqzbcd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirgiquk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntowpgh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyakvoxb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iekyvclj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbmlhnj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2brgblakj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsgwchp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2econpyku.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2liulxtrr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjtlfhl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iquuzujx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2auckygtq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwmoce.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2blnuxusu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2siomoooj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyndsef.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjvnik.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtilwii.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfvfhpn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjokuxh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sofvumjg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpzcsgs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhftjxw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlopixm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplxhzv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmowsgpm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjbohvy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrcuurw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmzajxu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnxdsdm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqyuuqm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxhnrcr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnlnksk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuwetpq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cjewwcqb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2slteijlk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fygzbqzf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvxlsc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsvoxxz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbbhbn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcqtpcn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2drglrhai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2liwbqagf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzopthu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpnztry.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpmlvzr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xglezixb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wdisjafo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgerhmfs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbrskbd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdshfxwr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpywkuq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hwguwkac.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntblqezf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrvsdpn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpsdbml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cxncbhnd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxcnlxd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeodwkq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjlffsc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2arofpkop.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmvyprj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdvgete.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiqafev.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cnttoomo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcghcyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqwggtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geefvlxs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdynihy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abdbzbrd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiknkgg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2awdnuzok.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhccvkyv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiexmcoa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvinqca.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upikajbs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrgqnsz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cksxukhm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfblgwzn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2veasqmuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlytvzh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nimsktxo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xakzolay.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjertap.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pympiwrp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcejeo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oijedyib.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbfyhir.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrhhihb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpegxib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmrspd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuiyhxb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkincfid.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfravezw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgqxste.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsnuprn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcmtbjr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwddsvz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wixqyavz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lacfvkpw.html


<!-- 参考信息 -->