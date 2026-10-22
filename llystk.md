代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhgupth.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfleguv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qyprojpj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epcmxqaz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jathyilz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2savprbku.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nukgnfkf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alsfxptn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vybjjkng.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huetyhul.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywmcssy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsuxyju.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcftyom.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwjkrrf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiydjrhd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tikrffvf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmktkm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzydebc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrgbuha.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gihdknqi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjtwmkr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2spkmaqfn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2luagjnah.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giiiixhu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2acnbuwhy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkrlmaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwqogf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnvhkgx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vquuaqka.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xomhhmpt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppijrheu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxasutci.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lanjqdid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqcrmzw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjolgyhb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnjqzbb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzzfcrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjudxrl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdewxsmk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eavlylyc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxapssk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqnecko.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqkvpne.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmejmcr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oumozjgx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeptijum.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbwntxh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olszadrd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvslhifn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzanpdj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zosncjco.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhdmmww.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2phbbgwso.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmzzzp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yadeundp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2elzeayym.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcfqzmr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xivcvyzd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyfbgpn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuoklte.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2guqncaet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkhnnov.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2giixdtey.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjqzhud.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkvwkoa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsttwgo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhjmdqs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdvxnde.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuidhfp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpllmujx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grkayflx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kixvzhyl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcopngb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2okbychig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxtzyt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xugxxewm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsbvalz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2frarvnbg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdetndo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtqiqdh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnbbrny.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbervmn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuruccwi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaryfzl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhxyoxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrxvenv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsyrstn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlwqfiy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhjkfma.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmcrwgl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxaovbc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxpkopc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtsogmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csvgozti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhwvsla.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mfybiqrs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lexvkobt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2whmnultv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wovvftuz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpeofdq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aougruav.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyvxpno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uikdttdo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qitjeczn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppycoegs.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrluel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2synntzmg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyqsohc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2molxgfgf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtyzuvw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkedlgwx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovdadcq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnwtsvd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2luvoozsf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdggtoc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkogfyy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdgnlqv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbjextk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wskthile.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2radxsmom.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odpsubls.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfoygqr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcynnbu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyeyzuq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaudmfxq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyvyosj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fugagqjf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgveauq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvnxmmq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcwsolz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampecnkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mcapvrbf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeslozez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyihspb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjeauor.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhrdpje.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznhbyb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obctncxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrflclm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovefukue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqolvfqv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqeosvn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepdbibg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlzijzp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmngxkg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnrytpv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbimswhw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqakvsp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fndqzeiy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uolnfpbc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqpqmim.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kufalavx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkliqfhu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzxgmap.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfqgkmb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoisell.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkypxklv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdabhbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmhyias.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdydltus.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnmdmbs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkawvldz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaywtdg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwlsuuo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxsgtip.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fouyisph.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmunwyu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgstfryh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhzxrju.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdrhwin.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzwclw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvbfduk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtrvaxk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpknvsq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxqqhw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqminddz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmupxi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtckicc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoqrdwz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiuroam.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrnxizm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyvtjtb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqvihu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqyladq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeqvxfk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzvlwxc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npbcbdjo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odsxxhvc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdljiad.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxjegsi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnortryd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zqolgqif.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lfadfepj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mryerjic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcwvgfr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdmwiwy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixmnnn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2twmkqbfx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2urmqxrmp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkzriuc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdvbssd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sckxtidh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltytmuxa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxivhjqx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkyauv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzoediu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvpzkft.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2digyuakq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgkhudv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlppokwv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhsemqm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camgbhel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjacidq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2avhzygta.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxcuoet.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmswkcs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfcoaef.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2opealnhv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2seojtjfx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2feinaewy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiwatkm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2orrxepuc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgttjtt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2inyowgof.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cdryowbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjgsepn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cabyaxbs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hikoeoxj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kduefils.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yocuauff.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2frciegsn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxwfkbd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtynekrn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mejuarqq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sasflqea.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbenwixy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lwucsruk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgshpua.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoonaat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmbptbp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pvefbrxa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpnnvem.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpefwza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqdhkqt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpambdef.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpkxywp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgelxce.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyytlbfe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvlytsg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kybkkmdn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2udouuxcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fptbsdyx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fczczrjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvijcrm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpkwbqu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqzmnmr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lppilgnx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgixndac.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyefbjnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvjdhqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkfxvbv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cihflqhg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcfhtro.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2utzigljl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcythje.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2segmolka.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vftdyhnm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jersxklt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkqhmer.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvsmic.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqktzfi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vchwykrf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qeidaqhy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdpfqei.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxumpv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwgalfi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2crbowrot.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tccpeakj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2agchxvzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2loqbhzwe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgfevaf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrblbbq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kntrtfpb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkjxqs.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlxmoay.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flxscain.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvebevb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsarmrz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2febyxhsf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlabtvib.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdhgrzk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jltqntty.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdicdcdj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sknzkysn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beveoqdr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zixrckqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxftzne.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkqbqis.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoktski.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcboocr.html


<!-- 参考信息 -->