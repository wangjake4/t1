代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycslgovq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkbyiae.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgytjyaf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nczukgjl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qluiatli.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwoqryl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrolxyt.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbjwqlw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nchqbkei.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfpitt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjgare.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjiozen.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwfsxds.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tarmpixe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bklxrfqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtcerjw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwnepia.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnjbwfl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtlmuql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsejpdtc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dilkvnrv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2htjmitdr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2taavsdln.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2retjdmvu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzityb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsdbyfl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2socazess.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oziiewmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rptkkbov.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhnynpt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tadexjyn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2astfljng.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqlqbti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljtzjzg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqmjgwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2llfavcnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcdcyus.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eenjqtpm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgzbbzm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwugruig.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgpqzik.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gntznlyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2futuyjjl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpshndfh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrsmamv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aczjjjum.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysagbnam.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqarmbiy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2farsuuxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdvbtet.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2waujnbwv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdykaym.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfgpnbl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrsnbc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fttvjjbj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2owijpgya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgejed.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgejsqa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjyvlad.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlzwjou.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcexrjr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2crlaiapr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcihpai.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qomnfqag.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxfaeft.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzwaqfl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jajnmwji.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qadrpymz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfooysmc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhalrapz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozwsxe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfiqtqd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvoauiz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhwmfyh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqewhzzi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oassypkt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjeulen.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzvlfjt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gldqldhm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqxitlk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2akeeinvl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ythlgjnd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqweumd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sygrecev.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drezvplb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgmmhkk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqkhzxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uosaitjx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlerwgt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huxknrdj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcoipzk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2monwkakv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2thapnlxq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynvmdb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsuxxpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzgdbju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xewxrawf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2befzteyw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwpcrbt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpkyikw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgvnimj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpglylwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hchlgvnf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qboiomvy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvghyvv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvekoid.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzkuegs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfsxlsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whkjhxxj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2widbpqsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mksizabn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfazyvk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmqkmtc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkyyvtt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrmnuhq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkmumwo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viwtivll.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgvdhjw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcwzenn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sblnequa.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkigdqyv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvddpujv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teesdegh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxavqje.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzclmdw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qblpvhwm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyvhfsj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrutipm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwthyaie.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqupghe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaiovhl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaqtdng.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcaqlcq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxvxtia.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkvofcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jtojkywt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfheqgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnnodsz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2owofgbmh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkahrho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzdfxte.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgewqnq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeipbjp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiittwax.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2agsmjpnf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvffsgs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucgbti.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqiezah.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zxourdmx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxlquix.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjanuxvu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuktmpk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcvczpl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbldxnc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fcegodbh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwrvrtl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpccdfg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiqykwc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmulcpr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymptobac.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icgmzrii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfdcger.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xczsrygr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqakvqcc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkozpnc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tpclgjrf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xszahusn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvagpws.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwwcniz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kefbxixq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfopfdvg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxjiktu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yykhvsre.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jddckgvp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlasxejl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2okjzqnmd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyumgrj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwnmpsd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgnhyw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiinmurw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfooad.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiokcqj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmhccqs.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbztjxop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfghpdx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbebqgee.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbxdja.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvzbjx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbilvl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxkheof.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnfrssq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnkipsq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2oofaqdik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzecaqgm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmkajhh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zsojhzax.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnfegoo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cntbmjxu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmaeiuu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjbhwei.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2isdotdki.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjarbaj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfxesrd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbndybq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezymrp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgzkzhi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmcceo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2roylagmo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rotckhaw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvawtpta.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chnwbfgp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbtkrdj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfegluhl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczfxmgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtxblo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wksikphd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocddnvym.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alsihicb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdyskbh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kanqrwdj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyibohp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nltexkwi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2plwvpixj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxnceqt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yltvcjvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxwumss.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjxxqjs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvbadmn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oldlmjpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hborzppa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xmchmvpu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxdapjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnykcbsc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anowrzbw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmckfmh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeppvul.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjwdhcx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzvobyr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfpivcl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqscxth.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkpyqgy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjjgdvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsjtynm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxjacgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wjavstmy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeftqyg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsvguhz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2busfdpef.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjxfoqr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2haarzmhf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpwpvjq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxjozvj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlcwnmf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2axoberov.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2asgzepil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldalxqbw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrejgar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsqgdqf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxhgzo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsficvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqbbuth.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxumtrt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmjjmso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvdeoqk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xekxvclv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtplcwa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkamkszs.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqcxjtf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uompojxj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xefrjnvq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awknmqyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnwaicy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfshqmfi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mqucptxw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxjuvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcsxgpu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eggyjzqy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvqacfz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wutoxevg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrpvlve.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwfmzxx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoyoneq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsjxzqb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2djeyysno.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjowtug.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaxrpbk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnobnty.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqrnanp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkllwfg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiveefa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysijfabv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kospcfgn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gavehaab.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrcrmmo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqzuczz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgumsua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqjpqpz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzkkhck.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fahpyyof.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwiunop.html


<!-- 参考信息 -->