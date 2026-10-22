代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucisxtor.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrtphvr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxgknwy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hslqvjsd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqdppyn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnunxqfg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyfsuit.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdrpatv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhnidov.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uekvmqfg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2aiikccer.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emlsrype.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tksgvgrb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aezrvpmk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2soyjssxg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpujgyy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdkwctr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxldhche.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqbgfn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcyofuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sddtzgur.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2epbtiifr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkgirkf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dadpclmq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoatvnx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pitalyxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcvhfeb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqxexij.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvxdgfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wimuplss.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvckxzb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zstocsui.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaywbdgc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhkxjqc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsuexzp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kciujlec.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2awajtygg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbvxff.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lamqjqcj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrgrdwt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kobnyyin.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdngheef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuxechi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eilddcum.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuogrjx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnxvzan.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceybcmny.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmdmkqs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xudidjwl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhciyprl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpxsnip.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxjpcci.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnovya.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecomymad.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwegeeni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgayjtu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rspevusm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2goedggpj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ungrjqjv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrbkhst.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2micphmwh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeyyywa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbjrpls.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wabyyyly.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkddkhol.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxumquou.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbzdlpq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vegxyiem.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhzgnxy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pebikmum.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlecqec.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmftpjr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkzuiyp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqamhvz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktunbwfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhnpyuz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrrfdao.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkkceqb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xldfcizy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiupovo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fplijpbd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrmpfiw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hukwzkhe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqhsdbv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehomvlw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wirwynei.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrrxgsy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omccgnxn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmhjbck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fewwhdki.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjkhdvk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lilqnwhz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxqyqfx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omvxhltp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxqzloq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdcuhfu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lmybhfho.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmlsgqh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxovkvsb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2enflzlus.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2agimapiz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcolosx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhuvnqy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zddskqup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jotsqeay.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pbixpnqh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoarjqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cysrmadn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eggmsfrq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2werhkdjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpzcamp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cncswhhx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcwnfid.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imevstkw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2risandvt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtruciv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muudxsgz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mniphxbz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2auzssgig.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyyomdc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqufjgu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkahyjl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgpshsl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkzaual.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrmcxgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgvzpt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvrnfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdvieot.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffckztc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zisbemmg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mylahfzv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbntmjo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhugmnzi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2omsqnqhv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwaaiy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2verxsccn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibondyvp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydifzowb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2udkqxwsj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2njyrvbxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlauivw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiomvkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrahlyuj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2empjrdjj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdemnob.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbynfvrd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2foknoenu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xghmidln.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2opgjspcq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reehzjhz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yczlcbgs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgknzrr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfuiijy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uzecdvnt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sellehsl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwarvcon.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2azheogdt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ighjncha.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzoeyjs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bloppkrz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgaiopl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sojinzyw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2raqbucnk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrgxewj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwnvshi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxwkjmf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcieorhx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhyjjtd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kumuqegs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2txgjkked.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfervsf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qebhswym.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcvswyx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyuudpy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xelbdiga.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkiotx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkjhflr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swxqvuqw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyvvdfm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfsgkg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rydomtuk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrksqga.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eamfsqde.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2taxqiqyy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oriiulnk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjehymui.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwqlvr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlywfwbq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqddeakr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiyrstn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrgiqzu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itoervcg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvybtne.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sobzpbod.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlbnygq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2byoumakc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gasaydje.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkdiexv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzbjxfy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oczztapd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sieohhal.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutldqw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfsmpi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcoidqr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlirfqpn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxgpyrj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zapndpxo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rompoozp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmhesoc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjgbaec.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwexaon.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xadjdorh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiapoip.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apjyjxrw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edncyzvl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdvijc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmohrra.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxgaffk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngzkrki.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxsbtsk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tneshbri.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sawskbcl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzaltlw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfkxan.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrjdfwx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wqckfykz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2akagnkkl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bueqmhme.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwyfqob.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zrorsruy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zavotcsp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2atmekyfg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2boqcavxr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnnsqmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoabopmr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2suxmkqhf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2evaadzgu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkzxola.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynocjooo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeuvtov.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mruthlmq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvapurp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcamjjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbwrotp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kprptsjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhvjvtu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atvjqxdi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxkzndy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fekjjqkm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2porsdehe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdbfctr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnurcdd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpjuffv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mkljqzua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpajuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnsvgcw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnrhbgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwannac.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yxepwdhf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibcynjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjonwak.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdrcxuv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dopuimnu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rawnywre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhundvu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2futysbmp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmymhgk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2coajzapc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bggttufe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpynqaq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2herpsphg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpliqlxa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amcwlurg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoeshtx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoxonqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooilccvc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqaecro.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnteezor.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yztfrwls.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwftohe.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2alpavlgs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2opknmplx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2prvcbtsm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkanwzsh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aycrbsdb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkkldqu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wccfizif.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyhbuqd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdfbsqg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcydakg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2livedfnt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmfarvp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zspbudcn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnugzia.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhcyny.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hdibxuzu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjcppxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkumpsh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrqhgn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isuuwatk.html


<!-- 参考信息 -->