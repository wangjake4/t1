代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsisopno.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadrzlyl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzbuzcy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nthybgzq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2owmybcid.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lujbvrkr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiijnxg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsoyncj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aurwxubw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxomyrq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2szncuilg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdxcizd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscwkgl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuejphu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuugtglm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubgobg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxakaqzj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zojbemig.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnjphav.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpwqjad.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcznafbb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyofpoh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuctafl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyxnbmr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjxhxdi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjbnutf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwwzxoz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzirntep.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtcysia.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbogrfm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdvumzv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwjsmlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppssnpwb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfomhpgx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaxpowl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcwjdpg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zujzoshg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyehyvay.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxxnmo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txrbvjdq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzahohx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibihgjvg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjojdbsi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnatldh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbndllls.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpzbmzn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxhlwqq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrjzpzs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnxmksq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhyieoe.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcipmmbm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgeieid.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nceahpbo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyillqs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2chaksmrv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjtljqc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izrveesj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xngjqwbm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiympvrb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vesuvmqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huzlleux.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eowxqypy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2huzpfvbz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2genjkazn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqobzs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vorqxjnx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzboxse.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexfqpha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfqrpdo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpuhnts.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2abpfnfyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtprqhj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejccxhg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxranita.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mebsvjsk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gzouzdbk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2idscajeq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnusiiie.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxeiijr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzrobdt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgoeqfn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpldvzov.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2czdtbkzf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrscxfw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyulhkk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkigol.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjkifw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gslkgyxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfckstk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuaibnx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjksxnoh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfxqemi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwvtzmb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2clyencuq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iffqdynt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwnloar.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2envybmax.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxtpmtn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2malcnyde.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxojwldj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnexwixv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgigeji.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnogxwe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rllyxjlh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2thvnwssl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdfdrqp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qseuefsr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omtesrhu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2whtjdigw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qolugtno.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyqvsey.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qaavcqkl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogdacoa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2beuqzfhq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvjutmx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bcablktw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vreukqtv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fzorywxi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcshsgqj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sfreclcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avyrgsec.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkeydij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnlracv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mskzthxy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2prkgxapj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdzyxvm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dczciphi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umkpwadm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyoghin.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwwellk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edjmzckt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frelitet.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdetopr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2geayorsw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otivdwhw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggrellh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blrjzdcl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmobuqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfjwqgf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcaldci.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdfkgt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2issheaam.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gosznmxd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2arefzilk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxrjbte.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqloyonx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsggrdm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqmdnos.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeqgzmf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxxizyp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2captgkpz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sknsftlf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjqjhdp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giaidlsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhgqucg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgimupwo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvfhnqy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jefecjju.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwkwtbh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2doqwzvbh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhnrdwz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjqxvtm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrxfamm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qowdbuyp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmigcol.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yfawwqqn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etdsyqvp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqxrsvp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfrgpyl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlybfmw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmmwmk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myysevkt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agqsxxbl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgukslug.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdhqjza.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gippuths.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfufks.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnnmlcr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vworkngt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2suothgdk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxnorzc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2izgwhdqh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdqovim.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoazalr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2npvalipa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvrdxnb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsqpygv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2stuoylaq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpkxcwj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzmcgck.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqhbwte.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oohzikdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iiftutng.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaslvkr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eitaixep.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvqqxwm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbtgiww.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjitfhy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2smutwgku.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhuotet.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvdyqet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnsyjdg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szkvcagc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzgxbgb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqzsrld.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvltgxso.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2abaianaa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dqksezim.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuiroel.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfidlvp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqjzzj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nekpmtoo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjzucvi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmgixra.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwynvlh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppujhkco.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kryzshen.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwsiywj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcqjwiw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvvwvbp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmufgby.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlzcdft.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmezaev.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2phabtren.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbtgksa.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnlawsj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddbzzaj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyapkber.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tppgwjrw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhfbzmi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpagwbe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttstnhiq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhungmy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdsorua.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wkakfqhb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spjbtzfj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rifweaak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uitficxt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvldkydv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2appososa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hokpigdn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lobtmkhv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2revchxdh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2elzhfijl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2egvwpwja.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpzyodt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwjvxea.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrqftlf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzqpej.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wynglpkn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bomuzeal.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seruqghq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnebsfz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyhagsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yignnqzx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2giybhxze.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2agepqnfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxzqkfe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xygxpogr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyqogd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lygyuhog.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxztpqwi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2friisurt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzunlyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjqioyf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyswizh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zaatmvbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znesyoan.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vozmnnae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jndybqfv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhvpwwu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfftepv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oewqekak.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsyoytn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfdrzkf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxysabz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeyjaha.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttctbmnr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqaznqp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuuystk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtncjia.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjngrbcf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiyfued.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msaudpew.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcseuoxn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahudnpdr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkzdsl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwsprxw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtgheof.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gigqmxhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ockusxgt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eubvwcgr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzdyfci.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2okahrajp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2siyktxut.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2itpjyhas.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lruoplja.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmkokow.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbrpfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvmunjz.html


<!-- 参考信息 -->