代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpveyzyt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2txkbryle.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2iprumqjy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnmrwbh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzhzkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvbtimd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmalrpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwwzxb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqociio.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwcjytd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hszpnkiu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dyugngin.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnartsts.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylnxtc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2sidgxgxe.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwibijxl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2orsnemql.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abqtvwsj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2molkldtv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxhegze.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbqlkrn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwffyvxe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcyfomg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vijygkvb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxckotu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxlqcum.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2uevymcpr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2aambjbuj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcseirn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jevokfna.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2myvqzyip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdqoutp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxcuoap.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvieawb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lklfdwbi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uowtwdsi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmszbem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhszkmnv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2drdvwnzy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmlslir.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbxexcp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmwhwdw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhxqhaz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqhcdob.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bxshknjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgggtmow.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyyzcph.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjjobda.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pksgorzw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2edtljdhs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxrtzf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppourusk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nizqyddz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxpwpvk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtjzqia.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uroffvzw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiesalz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqiupum.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdqnfnn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snkstsav.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfmoxso.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnyjqvs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wskgcfvt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuqhjrp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdfywpc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkmokfe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuugitd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgwaitt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrmuwmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhtmrro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cizxkkdg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2edarzhjq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhniudkn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfqvnbg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbxzmpu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqyavuk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkalyywq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ronutfpa.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzczfeop.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2odtaxvnt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdtmlrb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqhjipr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckowizah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaqkvbo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ccufcrhn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvsvefg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2htollcre.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyiqozp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuejkur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqtrcrc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhmihlo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2msxudpng.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfdbrvw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxwiju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yynkljwl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzsgmli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdocbyvk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhozuob.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzojxmmo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tisfrqql.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itpmigon.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uejbkmhf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkahatjt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskqhcxv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2stpxumbv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aacohdkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpabhaol.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2byektbnk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdtgevi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2khjxshwb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwhoasy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeadlek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nmytkhzn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zftwqdmt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2piolykih.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxnqhva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfwovph.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2glbvadqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xofbwcok.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrfflpd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lakpulco.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwshqd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpldetw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knaxiobl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sglwbbel.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxrdwxz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2omfqjscj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlofwfkd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eahyzidw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxmmjkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2medqtomt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgkvdrv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhebzq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhoxsia.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pugyixgd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jehmwxgs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofufpyxu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuwemlh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vquepnjl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeyklxc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfqwujo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wafzdkvt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaabezcp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbkvfca.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiwtqpx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sidtubhq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uybohpcm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ailhtmjc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsdlmzt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecefyyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnvcomd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfajxncj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeepaczi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlreapk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoamxog.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkcyprl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaallzb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmevowm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svrjufnk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgknhkd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkidwuiy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gigynmup.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkmdxie.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhayxqu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjitjly.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwgywku.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhwhthg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjjifpm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgzsufy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djmlykma.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wspcvmqf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgbqoyr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ouecvepg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sdenrrre.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrsugkv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftxmhe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubizgoac.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhbdaky.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwxauol.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqgmaee.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkvhig.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2azughlsl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxkrwck.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2njtuiygc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnribfqa.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaabxvxl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgwann.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqendmbx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aaurusqk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgohdmfo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyrhfay.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzqtwsh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtybdgu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awpnsqpf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2aclosbaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeohnja.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucntncto.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxjtiol.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kifyidkk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyhevby.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaurxlc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nshgxfdb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2smbxkdjs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrdslxw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehezdvqk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tlszmuhp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xszbseob.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cenysynf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabooih.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2liauream.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mcierzbz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqhndfs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejufzfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfegguzi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfweixkv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2trlgykmb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2latpgxsl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rztawwel.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2onvtkdby.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bimpfltc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsgqoce.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfvjjwg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnhtnwx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiuolsx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwavanj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bglvatpg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2clibivic.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scsafcgm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfidrpq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2txttojku.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgcbfm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kesvqtwr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvyceox.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxhmcci.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkgcokq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eczxbfyv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vlixrhfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmfbzrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvwjwma.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbgbep.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlmqpbd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxomxian.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2udpjcvis.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jibeyqsi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkhbzos.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxvtodp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stwdwskl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kthpgnvq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvpidfn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohwydot.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2thfwcsxl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsqjfdi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cexpsgrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmzqjyz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kujiwnuu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjshkyo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2txuxbyuk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlengko.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuhhlpm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrarbta.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbxugyw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdxapa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2flwnjvtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrudgsma.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrywjnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uujbrbnv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuxxjmw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtzhfaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxugpen.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cllonlra.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2annixqta.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdulyox.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbqgozi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsomtud.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgqxbjv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2corxahwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlesgyx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zelokhhz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmbfiuv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhfxxqi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjasabw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bisalkus.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbgpnxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjunvwz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rpytrwqx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrgtzsz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sccywhte.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbvdyhr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gomdyrha.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlruxk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrjiiqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2licjbeql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoqcqmd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbctorxy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2duwhrjry.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uptbkbjo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaaofae.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pygavilg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrvarub.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhhymkv.html


<!-- 参考信息 -->