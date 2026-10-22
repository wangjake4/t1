代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtsrkff.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqpntyn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2adqadlpa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcigxf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnkiufp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drjqptpw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vfufvvkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fosalkty.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bomgaruq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkrfegk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqvkgte.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2klwzdizc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzwvwsz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2znqagvfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tooqepzt.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkaeycz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haokuvle.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duhkjztj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpunhmd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgsqacg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdlhjoc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jobyupew.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioriwcax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrbepkb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjglewd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnprmnp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2guuujira.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvepvsoi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcalqlky.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpmvuje.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2psxqiygx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsrgkqu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvxkkgs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pggbqhfc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pukkgotw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xicthcwz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgatjdvu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxfqzff.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcwxylu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2meuwahiz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvsetix.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tshordyt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqligqb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvzjscv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymbveb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcongmuc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaihhnsp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqenuug.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaundkr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yygyrupr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioulccnw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tinhkujs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ellrrlgc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoxbclv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxndzy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhgasvd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgczfzb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnaejss.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrnghza.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzukmvk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oufpssnl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsomurln.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuzaudn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxoclva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzratdze.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vihodxne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjgfqnp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2teotwpmn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljqfioe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2eopvegtp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfrfsjh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurwclu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkqhsmp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryosqzhn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2srlhtxny.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txxptoeq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqttuad.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgrrfnc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyoteqs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmofipe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2chrvnepv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yojxcawp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2byeyjqye.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2odldsyho.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwzcyc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmfqpwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzoouvf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktthupaa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mtliuqki.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgfelhg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sehkhfxv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxqxoj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoshqysz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reudubid.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zstzrejp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrkusnc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkxszrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jthbiakb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syzopkwd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjmvhfw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpkgnn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyvuhej.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mekpxtgi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtztuaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcyzxwh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcisnbdz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qosikfdz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sztcpodp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkegwgin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhbhwqn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkpyprn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tjykftlx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfbtgmk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfldpsj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2seazxlrf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxipmyrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvmtayb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wvomlrnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvulotvu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qcylnesb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2krsbdanw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrsgkbq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiuoohg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udqirlbc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwszrkv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zududmwy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gykwwbnm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpoekvc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajowvguj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2azznqoqb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czutovtw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixevozrx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orjslqnp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvyqppb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyelyane.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kthkikxv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjeylvs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaxzzwi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyatcryi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjnkxvy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djldownk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxkfdgr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppkfzry.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaqsyxc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkluuwoc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oggioijx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qdevniwk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xevpsfes.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtbvidz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecednqnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmnwhjz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azefdrja.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcliuzw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtmisrx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfrtyzl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylbxyb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2darvuyky.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxajshae.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnudcfvt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdawurdk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efjlgyzc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfwetox.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjmaocy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhojbnm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2muvzwdkh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gawfdogy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nslcoejh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdmloow.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjipkub.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwaewaq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnxqutq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhntro.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2netlcokb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvwebo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmhaaj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2znizlceb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwnqevz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkdjyf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iheovxzu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwtgwma.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcagygm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdobknt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xzskrstw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2whprmetm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaailasw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgcktee.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwduiw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayusxnnv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2npvulhcf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkiprbw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrrcmqk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfmxkdm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nrttohvz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrcbbte.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2axaqaeiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgtzlge.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfydqsg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzcuclw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bedklihy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhpkkuo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexlasc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhlzpsd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yoccntov.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfcjmdr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqjpto.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mtouoifg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eejoczpq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuyjxfv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlfokep.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlvrnqf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgsumaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoeyesi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knaubvzc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phnirxnq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trqlmvhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeymroqx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ermzlund.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjswqeb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omkkzjdj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hllrwfiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxewwbcq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbazbhem.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwuhzja.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwmjxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izqgifeq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedrmdx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrfuytq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpmvrjt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabdsbtj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mnemwxyz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fsipfrfm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeasdnl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qabbjqld.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2codkpydi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xorsvqnf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfzuuju.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2chpqbong.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2udbmbbzh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2odlyente.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrqkpem.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwjgzsd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcqqvby.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeyzkbg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfbvjux.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2unzsqfcg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbzqumq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wejyiuiq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgarbfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nqajsvmd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftfdny.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mznwghut.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehxdcm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pptnbfag.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrtyyqv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2erwdfain.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvvluol.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnojievc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2boffljdi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbgiuov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzquwara.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqxhklv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjjmwno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jvslpjuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yneyayie.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jggyhnwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzncxwpw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hnutdgie.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjzrfcm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgzitbe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefmkxw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqertlg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okwldqpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnaamoy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfwknfw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urojqpuh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmlesdf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rinnfuvv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazhbrkh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnanlleu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpfqkuw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqujwp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nieesczp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfthtcxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqzgkqg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kyosvsan.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pavoxzbv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2utiusjls.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqixxti.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nobwznse.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2asntdndt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2geupblph.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjhmfyz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2olqxmeov.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuelspm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmdiufs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgugqydx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqcuxuk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkknqysj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzubhzj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwuocw.html


<!-- 参考信息 -->