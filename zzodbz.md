代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxejfsdz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvlhjyw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqtlfij.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtltrnm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kmveoqwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvqtbej.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfokkyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzijmgy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqktwepg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjogoucb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2riuahjdb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnryhhd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnodfco.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbplhsn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2szrkzfmy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wootvpur.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctspfvtz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buxlbeqi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqmkpui.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispqlzdi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuiueam.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfndydkp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwarzet.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygatstug.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sradmtor.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nocakmrt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbhmkib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2usekwmvv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2duwmngfb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjevxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxgivsa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjsqjvy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtjwuu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsmxktu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2goqfbstr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsckrlwy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbctyndo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkdhdrq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjuawvp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwjbqva.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnxemo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vilzvnaa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uegmlqnm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xheuqtik.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2htqfdyow.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztblscjh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2moqsxbth.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkoeqhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npeprtzm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiklcuyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyjastk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfvbbft.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csrliurc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmomshcd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frzlkpxg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2anjvxuav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znvoyrtt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cotvixqv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrrbsju.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyrysd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrcpdke.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdappmx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oumnblxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2urnixlxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dehzjqbl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhgyqjn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gpldjgef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbshfsa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ummkrbwy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxsyvxx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnwwhlv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gaexkvcx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthzlsbk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwhzifw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakybdql.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrghtju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrnyllc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lotpceaw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2copokobw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyojmknk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxpniqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgayjmn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrhanl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrkzmgx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgtzord.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoreshnq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwtjhyn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbxherk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hawoujeq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfakhk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqxmghm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kydwtejt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2divtkwov.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhilehi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qinuwrnm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leadczcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxacuui.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzhitcf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzigmfja.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjcklvy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlenwcvh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpravat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpvrnzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyadcuoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2krmatije.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhptvmd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2carcwpec.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2obwnuzzh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyggoafy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2houjtsjs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyixkya.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xcndzrjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjdzvca.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hvndncto.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxluihtz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqgkesd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdsnhfv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvxzler.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afhkelmb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tymtkjax.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lobintnt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqbzaku.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiebuol.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimyvtpn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jezbcici.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2velyvisz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltmcao.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjvfagn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaacbzzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2juklwtbp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqqnuuu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drflndgr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgjwnsp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svbjpghf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qestsncb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrbnyom.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toysncvt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvhpoxi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nldrimye.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyexmfio.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkstkxn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqfushy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxsmjrs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zbudpnhs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjbvczg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpufcwp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2stbcgijm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2khointid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhxwexu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmcxqhq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuyumks.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsctvjb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2foodumac.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcvpvzs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qerlxnwa.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpvbwur.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdqbkz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnajlza.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxdyvtv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ststjtdu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hovidgjw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkksiy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbflvcp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foyqkgqy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuhowvp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfzmuyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puioqmye.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvocaqv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdepxfwn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbkwtov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzpdbwi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqwjhom.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hieojhmf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbunpfnw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2npbjedlq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odfyfgai.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fidcnknx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqypyva.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2icysbkdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wlemgzih.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjycvvg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbspgwm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hobjiunf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fclinvia.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epxjzfzt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpkqhel.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfcsss.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrodcxa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2agvugxbe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oslpcfoo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrnylrd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2chzegpep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkxxfzz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkukqnz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ualpwqpy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeqtioo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoiifze.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubqmpkw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvgquap.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktktzqcw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gejozsvw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmfurod.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvgthkk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fngkirrx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kztrepht.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kokifrej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhmvjhi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyjrljw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2keonqqjk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuersqv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlermhd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scznqazz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnogkkq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wypowiwq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbrnmkz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfgffdj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbkmpao.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvkjnli.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfwpzuh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnajaujz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxsowgu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxayaai.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihgcvvu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftszrxjg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnunaos.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhdfsuf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmliyth.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzmglyf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbblsvl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kpimncgc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwkrfxv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuwxxoy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nptyylvo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnuepcu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhajenc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdnnogw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthrvha.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkzhtxg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iddbqpxz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtujdznk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqmvrnd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gimqnzmp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqcppya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyrxjzd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlmrfjz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exptqolu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rezuqhdv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krugyvok.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvqrlyc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziniaazj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfnifjb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrvkzsw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uikfslsd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mydnerkz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxopapv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xneeujft.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsutldfj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlliutld.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2azuixocs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2svmygwmm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cravkeqk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbfrvoh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2psymtump.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtpvexv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffromc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeidfkhd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfkxfjh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsukeeor.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbhfyhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2natnyepw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabigph.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gduairrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmtonr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uefhbvix.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbxqywg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvuvuzm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kauhmzpk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzrhwvh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkfybzs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxdcquj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqskvbs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wajdmbpv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvzctur.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdgspzb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyupgyl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwaanee.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vydsieao.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvnwomj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwltzlyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pithcfgo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvwiuxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jphrimjy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcstbbgk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzfqbiq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvgvvm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cysqkaqp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zngugdyi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bywoqkmp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgfbsmg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsejuqun.html


<!-- 参考信息 -->