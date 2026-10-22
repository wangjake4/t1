代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cexsphpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyqktzj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqqjmpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsphmmgg.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aozikkwu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqkcnmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxismnn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lcncgevl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2naumopdz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uaflbtkg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yryjdknw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwfqshz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbprnaz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uufubsxk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2juqzaluo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtgatqg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwytefl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzjoyd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxbihzq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcivbzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2agfuadou.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btzlhdwu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxozxo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkskyej.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2glgucxcq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajncxxyb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkturomq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlezudrk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zylilshb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslmtzog.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eocuislo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfqrdz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbrzxwy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjyasdi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhufcqvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2arvjjlkl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2leutzzqr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edurikiu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxnstmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhsfzy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlmjzcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkwnusa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dknsegmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2melqfipf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqliogj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyufngov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmajlok.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaluspt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsupmkl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuirrre.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaudkcj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwdpqli.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqqtnsb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xamzgeeo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwpktle.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epewhnfg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqfbeu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kniqurpc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uypamcqt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtofofm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqmrxut.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyxspmv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzwczbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlrjjus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvcvlz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfuaetc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjdjmkt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bioveohp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnismyr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygvbsxn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2emylqmky.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjswuqdf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwjzhlw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrpjpes.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uubneyif.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwehpzh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2chxihedc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxtnfkd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqrqtmp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cakbusty.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2proodpnc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpefahsn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtzseg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kekeojem.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqegytal.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaxzoyd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onycuveg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2epeluqog.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwqfoou.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axeqblqj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hftiyepx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtotrrav.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejmhghk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbqqsps.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qicwbniw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqpvoeu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdhugdi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pctiluio.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knqvxpos.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnafjzw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgthsub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtnwbns.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwjwbal.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwffhku.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yikgrsxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2coapanav.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2klzrfopi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nkofowph.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bctuqvyf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jexkcjng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zogfkcgq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2huttubup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpszlizq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fctyhmeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvykcejs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzyybnc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ukedkkwm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slqykfpi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qygkfdsb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dooszmgw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyxtgdb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2itintibd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjicgzp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lorlytzp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnzlwsy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqofjtbg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mypfkbmb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prxzrmjk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziapqzng.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoecfgm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiisxsex.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2piefmpjw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwyqcgo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcbnpvr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzqlljl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeghzbd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxybyff.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvfhvco.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spmeibpk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ouakvbjo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjttllbj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbxrqsb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbcqxwk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzzjybo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzykbyy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kofgegyu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvubxdp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaqpphf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2etajzwga.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhttmjop.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrpfvr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqasok.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyfmnkb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeixkfn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojudnmit.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wghloblm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmuzoh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2azqqrsuu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjnqoab.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkerfvpk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfrbxrm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpjczvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2httpvlet.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwstodjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqxqkpm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpapbsuc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ykedtxlc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpchefgs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvhoonb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yazzfxfi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoyxvqd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efnljisd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yckvjqjz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvbihaf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhpjnc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvkajtm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2flweaynv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkisrbq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qjokmpcp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvzbuix.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekqasc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbssacyw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2celvriwe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umbpiiau.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrespqs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmegitzs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcptsxn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxmrhvu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2booqbrml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzrpuc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nagfxlue.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olsywfkq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyprkfs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlkbtzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cogppffd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zihkldcp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2temzqzub.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jacmmmuk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jksjqrgm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhybomz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvxmoth.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjuvew.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2thiejetw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pczymrik.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxxdlwq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tacgjaml.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvttsoo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqxbznd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2excaslme.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsnhzrd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2demthmwe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrbowhb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ebosmxmj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2islhyqyk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqoiovy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ienmblok.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meidjcxm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdrhrnd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmfqfde.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfwkwbk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2khbnzkic.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgvhgh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tubaqook.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpkxkdg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdyldnx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spitrnvn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhgxjyb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cdowhmqu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rulgkslz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgdhexu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qppjfnvc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lzplxfpw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlkhnka.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2srqlvzvs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2acrhllba.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtpkkyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxkllat.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyxjjxd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypouup.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kevzqqao.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcveansz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqirkac.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khvwmjqw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqrlkkl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsgsigh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztchzumq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoibghf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fabaxaoe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fireoncu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbewhtfv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfvuolh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2enwejbes.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuulverz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2khffjzct.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjmosi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vikgbkfp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mkinhuqk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nugiqrlq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2behesdtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaudmemn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqyhwgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vruejcex.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjpsgoa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmxlbad.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aitsurvm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhdggec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poijyzfl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zputlwzu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zueqpqzj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmcyvkc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vstsbqta.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2obfoepsn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyejwwh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anmguipc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdsagxx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozathhzw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzinrkzl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdpwxva.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwltafu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftutmwuf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2anfhflme.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcryfnvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnkpers.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2thcfyple.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2drdpvlbh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsygcac.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2feztwyyb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqdwqbg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpnhghk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxksps.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiapmof.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2firkaopp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2folvrmst.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdvxlsk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpshsnx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyulzze.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmilmscv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmdxwvx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erdsnxsh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2luhelwzu.html


<!-- 参考信息 -->