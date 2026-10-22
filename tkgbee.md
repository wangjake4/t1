代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbumrfy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eniulfee.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjmxgsv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtknplc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdpzwpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsjfugv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hogcqwuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmngfkyr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrwoayw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2azopqbnh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyovhai.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjzolxv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaewdtr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnhfiow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsqjoic.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vztieopm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbacxrzm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfulptv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lceetsep.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aroddsjj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hccmvrhh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfxygac.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccclskxf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qblltnii.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzpuzih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezafllpt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyhtmko.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmqivfl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ephbibrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2accybhkt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqnmzfd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqsjuic.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwectfa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dppuqqar.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxhykuh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsbpfxl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dksglrwe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxqtflm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiklxsn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnhpah.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cddxnxew.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrzijnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kroegvgu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2advlsmvh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2abkhqzxp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmquxtrk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcugowt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwhopfc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lptstthn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpefault.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwdcuh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgkqdoh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gikgktrr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biemkfjd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpmqqrb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpukzbop.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgcglga.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azqdlkwo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpewiyef.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jslnojtn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lukleoob.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bstnlvrl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2covvlzfn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtupjix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fioxqgbq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dplriorx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2elehxnce.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrmxwhb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxllqau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdopdzej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzvtxux.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfjzzmb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdskjkja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2befzhdow.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieildxbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdlsydu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljsuhp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwbiecd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spkfidbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iljwehpg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2woptbzxk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrwyyie.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcuegjm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqdfzff.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhefpkt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azrdtihu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsbyawg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2artxkazb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dunffqjr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwdgvam.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgynxki.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjthpli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2neghvguk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwzjdrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmromin.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qudyhdkt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwizpbl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsvlwcu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2horlmequ.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tabxwrsi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzgauxq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iazpfnda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzycmupg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoktdzl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2aokefhcn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdqswat.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaysqlif.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oytmpngq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcssaiu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfzuqz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvwzje.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxisald.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aylwpoas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiezpql.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbovhzy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmmghjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkwnbcn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2htgtltov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siyezseg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbugqdk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrnyxnt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmgwvvu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhewyjvo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwcowfa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vctedtsv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxcsqok.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxvorl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiawazl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoafjmgr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvofwcyx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwcenzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sixqechu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chytfizh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdrwicr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnergpxn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmcnuy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unmcbrsl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxdqxxx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoipgvr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmgpras.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgmnogb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubuadk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2znndjvnt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oxekgboq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebdckx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjydgp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhlhzqt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2napimbmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spliufbr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfgwrvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghhvcdz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtrixht.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrwsikd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvxkkql.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedkvhan.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mvynwrol.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmnylou.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqwhyey.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvigtfx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brfmmxqz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqohsdzh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xwknafdr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egjdygxp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdzhqyh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzjatdq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjuysxr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoxgekl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylumjxgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itigghlk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozjqqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kxthpfyc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmkrqss.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqvnzlq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgbowqa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvadtgdk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmegtlu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdzbmib.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iijnpcov.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zykvmkyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeccwqx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlziwt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2szepeddn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfhwyhu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xldfikmw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuweigd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utkoeeat.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krlpwcrs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpfbwho.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyhrjnq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlxzzfn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icswaygh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbajdxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wjapgvyq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huedthak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tntxgtha.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjwvqhy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrpvdlz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwljwnl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hozbopff.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsyhfbv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2swubrhuj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybtmfo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmbeeqh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjddelp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqwsuih.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvhvwqk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdvonqd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwfxpbs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxhhysn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qycshzsm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cgugsraj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irqldguu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehqbjz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alzcofru.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alzkjhlz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqgxsgc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjtzgtq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqmtleo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdjvczu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jupxxwmu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajvetzr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boyjzvpg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvyqxjc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qydhhhog.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffgjyem.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krlcvljs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2orvvbvku.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfyqoxf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzbczzk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2skmxmzub.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbqkspw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjbczho.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uetszvax.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvvcenb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiazkca.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sslgvmwh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoobrjg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqgzjla.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnlqhsc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwebnzj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2abzbbvpv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofctepbr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqulcsg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2piwztins.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbmvizr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjsjpwm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qyftbcny.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfyxxch.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcikgbz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqepsdwa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsxzzkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpwwptt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqdscsz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cengygua.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgxtibb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibdxfh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjzvivi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcfcbrx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2winrfyuc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpyzjwk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnocrau.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgiwfzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpypppd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzycteb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tcosfcmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ensygjjh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaqdwka.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfcfeai.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbaspqq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcxzjyk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onjlaunl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwysaqvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrzlwf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzwxlfc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqytaqkl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaxscbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfvpugp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukislsm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkidkwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psubxkan.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqnbugw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgkfxis.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2orojyanm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrgfgub.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jcylbdke.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2trxekgkt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvcxang.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkhxydr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmraotve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvjjkg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnmmdhj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjeadjl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrzfswv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtkztcw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2massluuy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrxmjri.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2findlllk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upjdorlp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbtvmiu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2anwryvaj.html


<!-- 参考信息 -->