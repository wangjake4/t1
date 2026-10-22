代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcexdfvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddscuxnl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fycjvxor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzezrjs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzeluxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyvwrbf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtyscqm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbxgukx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xatotonj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khlopwgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nufvxjgi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtsyimi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzujpsyv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmahhue.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrxvgzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbkelxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uocmmtha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzqwebw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eslenqjm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxchequ.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2idsbfkms.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmgkqli.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sswektxd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2efcucxtk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwilskqk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2snbtkpex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjhevgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xltikaqv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcccrekk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfqednt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjipit.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzjmrab.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xejeyaku.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbptbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjdpbfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmxybvf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqgfpxs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnfubrf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvomnst.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdgfkmt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2acxylkcn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrhdnls.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuofrcj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glxdbaty.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqvhret.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyghxsj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wptqnxcu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iulhfswx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmasaji.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjntvapy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuzmcfa.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtnbyaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeafmpkr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arnunnxr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpucmiis.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aargjupr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szvuvhhl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtvkdor.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2figelslj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkizzii.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrqzrkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwafisl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhwywml.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2upifjcpo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfymajk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgydveec.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfdlfix.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ussottgd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaddbpr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bomgjbip.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpfvwvw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsalxjb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yipmxeqw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxqelbk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyroerg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfnjchn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wujeyqas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkdhpqb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnenjtn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ydavacqe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2owvgbdqo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oblzhaun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeiranu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2guazujmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcbadab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmgqrt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxyamzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2coiweyvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crsnpglc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoysobb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrthqqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kindpzvz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akipzwoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tucbmhxr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlgtxoj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aygetbzc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aflxzinp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmigixbr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkchkpn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyviayw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zalxlale.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xezcyxhm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwqzoue.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkizvod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnxvaug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ofludrgw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckinvfsz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwgcqfj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pstuoqxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyllujs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjmqcoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xncpltig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvgrble.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2utiesajc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvdoemb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyoqajp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fyttskcl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfumspsp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpjiwjt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snintswi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvmpge.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiytpsm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kemymajq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxhzupd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmntbqda.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tadxxxjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovrzzs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wklyzrpn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvpcoud.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhjwacy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrvxskr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2liltqlss.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmowirn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxbkhec.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmfqayp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dthwwduy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqouwaam.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvixfni.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxljxq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2evfsgwbp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeszivq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpmsbgw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ooacfhrr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjnwid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xockgenc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwakxmvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxviflzq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnhbcuj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izlknaql.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2viprctkd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvmpiih.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fmykntxf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjkhrf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skapcmyj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etcjladw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlticfx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sycviary.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pyschwlv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmddevws.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtycinew.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hadpmuyj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbbhdjp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udaiiisb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdhfbzu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfghfoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awgvfejx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uljzebvg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuazago.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqlhesr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgbomvo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ligsbszv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dolclgtd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyarmatw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdfqzcm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxflygk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2onbxvont.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bayujcad.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabgbqz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpextxx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmsaeez.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tidhfkjs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izuoipxp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxrbagy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avmstuur.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2empnlffa.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlevill.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvuqtyz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2supqijvr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jsigiebl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xynwrwle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gktbriye.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnurwnck.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjfelso.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuncrhf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tydvrlus.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhdfjzd.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkeadof.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzolyqmg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgizifa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnqnspw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2okmujsvo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaamvsb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yooowpez.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2voxnhvnl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lokerbdr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bbymiodm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxgnlbg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzhcgyx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvmvikw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lguazfeq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rictqwzz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygyspis.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2aanuoxon.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyrmug.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfclkqj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqsqeua.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bckutuhx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyimgid.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffowiojp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrnftje.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicbofwj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krmwfvpl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuhbliz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izyxfjkt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdezceym.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlidmwx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2larguqcl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xoubygiq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2messpgld.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuvaxql.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gveqnsld.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xayqxrol.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhmlatp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2axbnkizz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zaszmzzi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2giyuqwud.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvgtrcb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruieejfv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqakpyvh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yinomtyq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2llvqeayo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rulekxit.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oicltcbx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fshjexny.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jyquezcr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyygcjy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2izwxvabp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhakfrh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2odkfcfuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrcrged.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2auhgrlow.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfhssed.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqmgxe.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvmpkfm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2usunbojh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkijzzp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2phlisewg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkkhfzf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnuadxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwxgkio.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obxavzdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvofywe.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2oewwyvfu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkyrlwv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvywemm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqevdpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcewbse.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxvrnjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhesibh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llwaasju.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfweuses.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2euffwfol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2slfpdvlr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrhwfjx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edroyhhu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wslrejnl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svtanzwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nixkzcov.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgkdfpj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzapraz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsndkkm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfckppd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlgkhcc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyrxezv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcrefbx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkottdry.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fazhxqsg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yftalyto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqizbce.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlnyica.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rczrqyic.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmkfadk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtzneey.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szddbwoj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgzzckv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wygcauxv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzirifp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqydmto.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mibrmvib.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wowfpbjt.html


<!-- 参考信息 -->