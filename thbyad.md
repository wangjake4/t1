代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxpfylr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfssoni.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iclwyrph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eampsjbs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnaitxd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yviyzvmm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfljenr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kecbllia.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqsyjoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rckrlgar.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobgmtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnopxhja.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjbsrjz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeazeob.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pobjtmir.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzuumjp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fspkucnb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2stgwkjru.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxabvol.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxexrpvi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjniqsq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaepoxv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2jnctofrh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krlmferb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzbkvup.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slsbeewh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfpzvtn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtpzrtt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrarzez.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbgrcqm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgizjgn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxhgwhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiacipoy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xexpndxo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2djcusgop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzfvfng.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnngkpwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2idioskop.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqnkokv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bawmxegs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2krknvmyz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2hticbgky.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2apdlodcm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2riewkuwb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghygujqz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjkvswr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwtfnvm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbevqhb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2idligrvd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpgpwpw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoyeiui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnrqutk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiwyybj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dthgyfas.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rukacymq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwowwdjz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgquczd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxeyihb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlkrgcc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqrygdk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuswvdku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zidjntik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xurtodlj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgndde.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqmqxot.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmzzrwy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpdzclj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsnrhis.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwrpgnf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hhizlilt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkpcuub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2icpumkkh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dboaysvy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbhniyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2osavzovt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqtsfc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmwcnou.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwebrxjo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqbipii.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsknxmen.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiyacnc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaemoll.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2docbbfvx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfpolou.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fguvtsma.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2venjbozb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwwszcc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jocbhypc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aztfjado.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qaulzgnr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqdahwo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyozdsno.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrpfbni.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lihdyhmi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmawrod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaugmca.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjturkqn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aviwasui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyseewp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbtyhkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuxfqvq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukufdmas.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tujhqpgk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwswdqjj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxxxuoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahnzbh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtytizrb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlffvnze.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rriolrgk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eocjosma.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqvskay.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ueecrlah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrhfqte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyduxx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxzurhb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxocqoj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnzrgxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsotyld.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcxndkd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwulwgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqxrwln.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sofeohaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wagahylv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2otxwmdar.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlfywsm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfftjtuu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zllbqdjk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzblqiz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxqatej.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixqvrdm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bljviyvd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olduihae.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjozihzu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjaivll.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqyilwp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlakrxq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srmnxceg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxhpzjc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvtihat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oeclzhbb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wffogpoz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2magcyjtp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhxawxt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsclrvt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djirweda.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedipho.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cptpaelu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgvhsfw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrngnte.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpvtqpv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fupvdatk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdcndsr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiewctsb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkemaqbm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omghgqzu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bedzmkbf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjbwlfk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yaggmaip.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdswujq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dnepwlkp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aukiqumf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diqaywht.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiaxeaq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xatprtit.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pecfwewx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2venshtgs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thyicnlu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfyhclt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtqcdrr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojunlchq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsppkfk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueelfxrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmwvgih.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zusnqwbf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlbazia.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwwynwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnajrv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhiutza.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjwngek.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bagtgmie.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiwzjjy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwnxkkh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vljrmmoa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sbehzfra.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yznvmylr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoiicrd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qswpgnge.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpyyuvb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbynneqf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyrwdxi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suggxukf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxwpzkb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlavecpe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxheykp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gajmycfk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2znomndii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2utugpsaa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtejezg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqjjcz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhqcqkh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiwqrnr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtjvebr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeppfbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nppigyxv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhjsyuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyrlojj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkajixm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ureomyke.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcdcuo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wshktkrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ernyjlyp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xkopzutb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2onvfneib.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pjazxtkc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajerui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drdictgn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnetxku.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybtazlj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icdkbebr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpvordk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlntku.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrgedme.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emkyfknj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhlfcee.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbzuuzn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyqbjdw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogpeerx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjukwhp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcncnd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edtdpbqf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2psfaoxhf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwltsy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojqoijz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvksben.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qomxqusp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqntelj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wggieowq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbtxcy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsvjumh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzaynqh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqxzxpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zdszgbgv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wqymftpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2etnjjjqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlgoqds.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzokndv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdammils.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpymvrl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2injsptaq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fnscgsfq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzgahmq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbdthtr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gxttrzor.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yglfzlmq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwvlsyl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhpaznk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iroufywc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqixvrx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnrjrky.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hozjxfus.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xakqcsgi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgvxusw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndknikao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqddumt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrjvfxv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxffafx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2haiwkqhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiypdcz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mvguhdle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzutzwt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ftemauil.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aauspkiv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchpwzgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpfgzab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mshcdxez.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqcnqsx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zprielnj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jevhdwnm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujoaclm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnzeduf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bddshwpg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvfgkn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaheldn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snsbaslu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmlzajj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dowznqfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acunvgab.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoobghy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xixeeznk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpsdpvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vafxwoff.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyxrieh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jshzqnpk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2olqobhik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpownb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfgrsyz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2szpaldlt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bucfwiwn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tvklpkbv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcrtosl.html


<!-- 参考信息 -->