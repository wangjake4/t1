代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbdmuyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpnwxdm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgunnvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgyhbzg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2etamdcxa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqcbtee.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2khzvkfah.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgdvsvs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suqjjnws.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjnweth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xegnkbcx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vensfgxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqnbmgz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwfuzwg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnuskio.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2musqhand.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnhufma.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunnhdhg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmlewzr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcgnfmv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwhhgrh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdotpmwp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqzqpxz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfkzyex.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcawfh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoeibul.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbvvvmz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjrpqo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pswrsiia.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxxnsjb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkqkrki.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlmrczu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdnovrt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpdvsmt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfuthet.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wciwxssy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cltmobnh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbgzzvx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dblpplvf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpiwjgs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzigmfw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrfnlcy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiljxsya.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbaaixf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isfkfjid.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lngubjkr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqmpcfm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2edvgulhn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slgkglri.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mudefkuo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fforotix.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjxkuc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqjykmi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2honnyubg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxpiulv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lloiflua.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izyigvne.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrueuzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpstjeb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sesccpmf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjbeemu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvnzvly.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrikxyv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2frnecpco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswvbgrb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aarfmetk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaldlvq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xplrsyaz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzewrrz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2attoywcq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aarzhnyu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxizfrrh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdfbqvf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdfjpbb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmljxut.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwleucr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntfvkn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2takkfbsu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxdtni.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzovyfz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2miprofgy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tiumulcf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dciypjwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpjslxm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfldxrf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmwajze.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpgaftq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvmxrvo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egqsxfzy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvncskh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnzmdjy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdabaae.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcuxfwl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bakvvmxz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zudnzipb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoxbmbp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dyupkgmo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkgstev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssyhrg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclicqj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqtvvte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrhicb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rauzikag.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vopdeueg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyznrwt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzlqfo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyxzwhr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2okyardwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idqsjntd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkhixvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiknqxpi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jsezsbnx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cuenwovr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ockfswej.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mceuvyjb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icwpmsph.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jndpzdyk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeogtyee.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxojungn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbwevfr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjrnqxj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojfxkf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxwvxwq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klgnjdwl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prodiaob.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylavoqag.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qakacpzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttutgwnv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjfsmnf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tttbcijk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhawnbh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrwlyux.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlkcikr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2buvorgzv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2phweqjip.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwbrkdi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrqymtk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiuwvgm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxhwshu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdktome.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyswhksm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khumpfch.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsazpbn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beehbwmj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2trnwxwsc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkngrzi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2noazfdph.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hqthvgui.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ncltxzoh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyppqvr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsisxzfb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytygfpji.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knowgpwz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mzepmety.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usjobsuj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwogyuk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybahmuwr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2girtxuvr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puyawvpn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmpzbjs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjnwrit.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkexcgd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgqmsaq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnagqdhn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2utureoks.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mttnrhem.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2edsofkvm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gisxqslc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjcalrz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2grspjnvh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvaopaz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlfuxcv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnrhoal.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2igdsdpwr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ovejsvym.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2neybgyrx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvyjvrv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhijoohj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtilggd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2todioarm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eftgovbq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2imdtvjbv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nitlehjo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncydqe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrfflit.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhupzckt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfzjdqu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyleyeck.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2actwkleh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxwlvn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odlkgxjb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcigbobz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnpfzss.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiuxpkk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2atwacbwj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqxxuci.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkwpukc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tdviylpj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlweyhe.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cmktltku.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhexlpq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkzuwxn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2meclyfjk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjpenga.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjfbsic.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaffflgp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktyyssw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lexatdnj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ailgpahx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2embcesvo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2naipznau.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ooppnsac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjcxcfn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxxcgnk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thatsrdx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upocrnrl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcsyvhc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgcphij.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzlcihc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wetmdxlo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsmtwbb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2omucyxmd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrhtkop.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wvovontt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpaaarw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bevgxing.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfhnunv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2frhngtwe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkjiecb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgcmkva.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hugwsyuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ealqmqql.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbalzckx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axlifyky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxbcmtj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnswkeh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtewbgbh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpcbjcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiqcbgn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnvvmua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhzscul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijltgyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzhrzq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nigtjdma.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbkeax.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlokklg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2egloxjib.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxvctzz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjmmhz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnrkpyf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjexbrfr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjipjyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiwbdos.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2utwqwhox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeaovad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geazahvr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnaruoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyyptos.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkasvkq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaswykuu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoxvhod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxompanp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecofcmhs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ollhfqdg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aohrxzoi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oguuvnxm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlyzgmj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qowrcgqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cigttgfb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klsoeuyp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziatccaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcweivmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hixmaipb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpaeses.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynolmkin.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiinpawr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zwipfjvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lalkavtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmuycva.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtioagp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjtbti.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lclvwcdd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclwndlu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrrzgoq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xejlyfpi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axwleebj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyauhvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pshhnalr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxjhsmm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diodlvln.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kasrranw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntmiqp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ganocdfu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbphpce.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yaktcqxd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zawkqkih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glonjhwa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niqnqcdd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2assrtcxl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbzrqvm.html


<!-- 参考信息 -->