代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdabdhwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxpfgy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfxolgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euzprpfr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjeylez.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnnhrbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odhbglyi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uabgyeux.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2owijcita.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkwcxw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwpesdg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrmmsxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwhqqp.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoskccs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvoxxyy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysznlnrv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msfplvfw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfejjtq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovczkjuy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbptgft.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2putxyfux.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfwlbch.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvlptfl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmstlge.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwhxjzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkudvmfo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoijgdli.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbvrkvo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2truvceif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tygpieim.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2npmavmkn.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utggrrpx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqxzsok.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgsmdkv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovojoake.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqiquou.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjklotiq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xndyynwg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfcajsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrpoabo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ianjtjyq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuvyeay.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjfcfll.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgebiyh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2euoozdkc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqswztai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkznipi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcnyhus.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itiwdngx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lejkixbt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2seymouvu.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxgoujh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuxwpti.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fitiuzpj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbntaxq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnhjhgg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huortylk.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uufrofbs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqggoski.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwehovxg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avmvtmgj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrmhobe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkacuijd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dukciubh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlqjxcf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrevnysn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsikpey.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbljnjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnxiatg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtwweqc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2brvldmqz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjvhslr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxflvxyu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrhcie.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsknbij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyexwwa.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qptczovw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhfmmhf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqxwtud.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hslasyib.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gupzawxs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2erfjinml.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqnqxic.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiflquj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoejyos.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2stjsmbdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqswlqp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmkmiqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpjvnkf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btftoqcj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2coldktiq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krhitwql.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmanzusa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2llcecxae.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlfrmlv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhzpbgi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdyqgea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgigweao.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rebqocuc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpbknrf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nyviucws.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzdajzj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2unontbrk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzooygpk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxouibw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlotxli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mglufjox.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgtaqrr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxryswg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2phisdqwn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnguixt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnmtbkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxwryml.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2paohcitl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwxmdmt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtvfywe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqpezfy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njjenyww.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okrrjpua.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeeeaap.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epxkrokx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjofkxtl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yloitchp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erjputzt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqybyr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fffpcrfp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idjihjtt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icuuaqog.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcdmezf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsedfwsa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dinlgrts.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yynqytuu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjbwgto.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jesrdzzh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxreihde.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tykybxek.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkjlbgs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfabxrx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmvsxng.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyenral.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2upvskesk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twhakaen.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2egccfnrs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbnnmjx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gilaihjr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iknfdtzg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hajmculy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obubnxox.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vldjdmul.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atuiraof.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjfqzov.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uyigxfyf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rrywofzj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqgqftl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyvyhzl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvggvphy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onhcfpib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xltqkfyg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqzjpyb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clsmdblz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dubpncou.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uihouzbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyefuchy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgnpual.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcehabz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhrftmb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qwleihys.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sksaazuf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsylnjy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmjimi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvdsqei.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2giaodpzr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfyocf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqpodhj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyjryii.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mddnrmby.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rcigslwm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbasvtkz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrxspla.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyfmrto.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2povdaomz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhcdybw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftadofdk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gudvagkh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2excwhjrd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmcdhg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iatouxrm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjslsld.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrdanwz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzrpwwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2eywgsdzb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfjiasi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphmjjed.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zloysvqy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoifugc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqohzlsw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2agiacsdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqysvqc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcczdkn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyigkry.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhnjotj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ritemizl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uylijvdd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2naoasjcb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcnrywf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zixluxsq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtmdufm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scfyjfyc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djtnjyhv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vntrezxh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edmlcuhu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdipmxx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nkllfalq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxohsgnd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbolheqv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfqnpxk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnbweg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rziyfkho.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzijhbia.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyucoyy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvyrvs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbncenf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgqzkxq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyhkweo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkpywow.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dorcldqe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sfedrjsg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qcshjanv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmovukr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sodlhdfo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnwmssf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gcknskuj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2peenjkbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2uruteybg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sihgbjkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptojyila.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2brbawumv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwigtex.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpvlqgg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cucqpsjw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2euozeibc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnbynwg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqvbjvk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyttddpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkpapae.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgznbgtd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzikyjfv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxulrnx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmyarrn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoeyuqx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2waabrqvp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlfhatu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvfplc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2btvmyfiv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbsefcz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bndwlvzy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdfzshy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuiutkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yriygiob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzjufoi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2slqfskem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoumaks.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2njmbjhzr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumymdca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilayjjvr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fccxsksw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdunimg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtjibsc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oylwberj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvzdsxk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuqbaak.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcsttyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmqvppg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyqevrz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpoeoyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzcfxbv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isswvnwn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2upyxmqjx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtocsrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmqdqqj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmnabgo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2anxdwjnt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zopxvica.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcwroib.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbdfezr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbutzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2baunmoxx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbbrbc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlamssc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izxzdrwl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcgtxug.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqziawje.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hebddtzj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plwnnpkx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irtrbnvp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqqltmk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchnnvm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcijarc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crbloqqb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpprsxy.html


<!-- 参考信息 -->