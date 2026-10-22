代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxosaadk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgsbfbc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwrvcel.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njnumhca.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fvingbcm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwlilts.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgshnxsr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2auhvlaav.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjgymzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edurinyk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pypwrgba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwqgytm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhiakdk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pawvdibk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmqcsx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kipcbqry.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlalxdnn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uanbftcs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsrrach.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeuhzwg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrdfkkp.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgjkxhi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuwkwrj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfrsayj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbtqqcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjhbiid.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dumocven.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgexyvx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoxramd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytavbuvj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjfypj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzeeevk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwawwbtc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyshvcl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhazeryr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zadkvxar.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmphwjrz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjpfjob.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwirgxar.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gejlsqtt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvqxaay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsekrysh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2crzquynj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbugsgu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckkhznb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvcelbp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaavvdet.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vksyjpqu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2btpenodm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ondyctrt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhzvipz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sefkofln.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntseodf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfshixe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaoxdhe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyiiafn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gifuirzf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krkzaydo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klqhlpme.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrsewmk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtphhhfv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vonmwhwf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrgtngc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnekznp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hacfqsoo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaxgcbi.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwarruuj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2suizoqlj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eghkqczr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bxudiqka.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2odzbqwuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgevfpxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrisnytb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlgwtkq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yunreyon.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqdbxxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuecbko.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwwicbr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuepygf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwrylol.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwbmbbj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeskgmrq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjmkpnr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrlbote.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dxndeoha.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ireonjmo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlxrmcm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aavrtbru.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvdvuth.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ammvqdjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tigvzhua.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uafkquei.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcezlst.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rtywwobk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcyqxea.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxsjkna.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjfiqrx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glznjhis.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwyirle.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leibtnli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpznoctu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmroscm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gczzgluj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgsncqq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbikjzp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvksovic.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlpogrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhhsxpy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wjslqwqp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2houowzni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2syutznrd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoqtfdo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bglmhsyg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tazmfcal.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wqphheuo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuxnkyd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoptvrt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ezidginq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vccvdwyt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxmklps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ermdnqvy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsaxuwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbftngn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bycrbvlx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzzkzbg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvazxoq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vinuxnst.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlheghtx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nldkziar.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyunmzfq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bexamadj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2favimfqn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbripnws.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cembrgpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyhqcfl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxycspt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnewuyl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgozpn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfdjtuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcgfnxs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkeaxvf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iymukzam.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2whjprxmk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzhvmxq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oznkzydv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbclayk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsgcrpc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbhwwsb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkwphdi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtrtfvx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwbcvan.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2spghofxw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvbmavt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwirpawr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgfcsqf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchnwbqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vithagzw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcovoxay.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaubsbp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cutgmcza.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dugpuhmx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2helsokbi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwxcqt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bavzeqrw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqbgoiy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aldvmxxh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eelndamk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuegtbo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eoefvvap.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2phkugqdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjcbxkv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyzhwcy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzyszxw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtizcarh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aexpyouj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kywwutez.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrnvknt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwipxrf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmimklys.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xffymzoo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zehoqabi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tysqdouv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kukdttql.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzcjsww.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2acubggly.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuwiraw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zovwwyly.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyyodff.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmgqpmz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmyvxtq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vihkstfp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krqpuofv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qunfemcj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwugrgc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiobsql.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2etdfvwmc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qijckpfp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxazjuhm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwvtivc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvjrubc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgosslx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oarnciiy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bywtfcru.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npurutuo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2enqfwgxa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjruebta.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtypyvk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbaorg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iivdtkzr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mynfdvkk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hojuuyih.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2toitmfmg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lczyuveo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2icyatmba.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ixloryto.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqebdtc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frrxnkwu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkkhblj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aymqtvmu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvhsxqd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2riwakhxk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzrrzpd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocyotq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gblqmjqz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbryyqr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tikorwpk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2josycupd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfopqqns.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcxdklt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjarxgwg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrdwzgv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2razqclwf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcgtxsa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjkeyzw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lpacvflt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsolvbnv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaxiyjp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmbrlil.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbajgtc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2isuzachm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vdadnysk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cfznwclt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2shkjlpjr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsmifql.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtguhac.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arzefkmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmeucer.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqsdqgk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2blilrtcx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtceuog.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2joqoyirb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohegukio.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdvbrtr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2doejyndj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2muiuhxoj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdeancx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2juaadhbf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfjbabf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaftclx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2woemhflz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyxkfjz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nozybiyl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpdyaun.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxfdxzq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpcjtsx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2clbvpwpw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cacruqxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvtpurt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2krnfdsjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yarcbndn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzirzm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfcftvm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxetqov.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwgcboz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqiflfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhgekcc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgnsgyx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tokhccpv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewafipqf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeyirfq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxcnroh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuztvafs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaeeopw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvdjove.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmgykli.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutkyds.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxobmon.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxrwftq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2holwcnwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqprpgt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqamigiu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfbajgw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jclljmsx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqruleq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiymhzjc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwvgxkr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkshasbl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwaitji.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxcsxbu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvhfarw.html


<!-- 参考信息 -->