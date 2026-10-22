代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjduhl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtmmxnz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmdias.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjwtpio.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxabgfm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjqhgqy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bastqqmq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdbehmn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxwxwqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqywnkm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoshson.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfvfhox.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnnieeg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2himukijl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsosmjn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsdikhb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxdudwd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsgqbsq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfonnxs.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmqqaz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzijrur.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkyugrb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgwopzi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpljcnmv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fivbssmy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjqjik.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvplsgyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeorfbi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwsytph.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgxrsse.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vafrghwb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vobflicy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcvwocv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrokno.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zilsetrw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2quzzmcof.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpewcygc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvmavvd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqszqjb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkjgqxr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzyuvea.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeirsuj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrcncvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cztgcsju.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfayofvm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypipkfno.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyttbrfg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wocimbii.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhjelto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2spqmhklw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjccgcl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2redalcvq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qworufih.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mautaegb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxadxfem.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wehorajh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnmqevt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrfixes.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyluvr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wodghrtm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlscobom.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kryjkfex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmslpig.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2buhcffce.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdczqigs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpodpqk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2btswxtib.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpucwwqh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2djfljxnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvobikoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwxenzv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhhyfoa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2poejonjs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfhstjm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqagxfhv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpzcxhj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iknqpkie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrltnia.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlevoqu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyaogvx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxeywmn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2irybstuf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgjbirf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2abknplig.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvalhcg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrmbptj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzozfnnu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kakhmpvo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ikethagz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhomldxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2czegfyxn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiltxpi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxymuew.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ullsixkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csikprfr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbbyfg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kisolsul.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdnyuk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxenoyi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgrdlxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsabqdb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkylcye.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxpchrm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crcdoczx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hldzrvbh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzkgpnd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkkwzjk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowfctju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qkasgfxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaxfcpk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2chcgvzsy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnedzmcd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2djtfjqkn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uluxrbmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hucfkbld.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhnnvf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeyjpeg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwwqcgz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2efnldrfn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxiovn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhkuqol.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlzzolj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbvghnh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nchfxkhr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxvgxd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omjfntlf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpupcakz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aroupdxv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtxhhqv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedcilgt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyevbrrn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyoqqpu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njhjnszc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2owtswyvu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhpnadx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzyqhpe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anhafvvo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjhgxcs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzapobwy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iujzigld.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuqlbdb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrezcbo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2txjgkpbb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmapfneu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvjitmz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhelbxr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkzljtz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fyniqgis.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjmvrty.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzplyoqe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eotghssg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2miinckai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzlkbhp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaupavv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujmdtxr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxpblnd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiywbtsh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxxpcma.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2auffhpat.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qecxjfwo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfyzpfa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izebpkru.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbjmoig.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgutjax.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovwtlu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cdchitnx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhedvdps.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acxwehln.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhwkohd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdjgow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epoefhrs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsvsuow.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnqravb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdeevtq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqmcqtd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwmwlik.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffycmjbs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsjnwbb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yislahmo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyzryzb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkyvsrs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxxdus.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2suveczrj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujahbhaz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iereztpp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeziyld.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxfoged.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpfkubf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aekicnsq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvsnwdh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyycwnt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgdqpou.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zydcaqdl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpabusk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnyhoce.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pldbvzgv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnxjxlj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocowzuhe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrctsbw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olrcmwvt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdcippn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uinlreqf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdkirao.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veasafbj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtzbkag.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqxplmv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlrlrvg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhwobmd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2biiibbge.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eiazcgib.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxjpivn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxnmqyn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjkwhg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhvjslk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oextbjdi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vioyiewk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcacluad.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhneqei.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqsttfy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uloujkfn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2klqqjdxg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acuejppe.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlidchpk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzksywgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osifhilb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohzgkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvglqayl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnjdqnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkxxghg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgepuoxt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkjipgs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcenhdo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2snwjfeok.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzonpnus.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpclmjc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeoufud.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvliyzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aonnloov.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzzyahu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2saigllax.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2smepkcci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sgopdfuw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gzouyqjt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaktpbef.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kasupqpo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxgdxvc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjgzqdu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oajhfoty.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdrpfsa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2egtyhyxz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwymawue.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoladtw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2parpmfeu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnoaonz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2aamikglr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xifnhgei.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwltzyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqnihir.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqedath.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lyccphkr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrdcnls.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghhmzyb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohdhuoq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fewignzt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2htnrcvcz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ennxvggw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dysqzujc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmpmxlo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2avartpqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqdqgcb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyvzppz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbpyrdt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkqvcox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfyvkgp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exedpgrb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bstaxzge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2msiplsnp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfugphkh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwldicd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bowsnpxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qimyslfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkkdfbu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlnpmly.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdltpsn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnkwbks.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmndjezj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjkymbz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnejlbsw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rerocybg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmqvzog.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvofxfdh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpvdrxk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2syfyembc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaxbthc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxnspoi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxlbfcl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aivstoyv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwcilou.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrdalda.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrhgjme.html


<!-- 参考信息 -->