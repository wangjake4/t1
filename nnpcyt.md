代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uskcygrw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uepclzgf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2jeokndsh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkdfbxd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsswdph.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfefqni.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyitfng.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzqvjew.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdybmyv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuigmsf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcecloaz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtkzssy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncnxmz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bijajbdd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiygnewy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpyqxyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbpludr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2aouujorv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzalfkvi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veyiajsg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbevyyxf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiomdru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdfgzsu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpeaktx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnckpdx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2baaqivbv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnborti.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tipgiiqx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oykpodbq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfpagbk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrdskar.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuxnayj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amcexrth.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phkzcdri.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlertyzi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aepeagod.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qktuayyu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npynrqdm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjutcc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wduiqkvu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuickqi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awlipkdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkfpjpy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhomtqkt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtekcjam.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fugkyciy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2enwclxtb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2avjpdmxv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtxdsfp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrthhio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdqjpgl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2asvlesbw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxurne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeccbftj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyuqxvp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoakixv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfydytq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xofhqlwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvbvvhm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2encizcln.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbsunu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyiizrx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdeiszi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoqcyfh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbcussm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwvcnty.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fknfgygd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wuraejmu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2apsezxuw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nulmwktg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxvqcq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbddrhzf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzwlewo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wdstmkvh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njkzcmow.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxuqsix.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqcbrl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkoxlw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kztukfza.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbidycwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wirdzpub.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjswfybe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbmdbco.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxehvor.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2trwemjsd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnwcski.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzoxofh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpksvnr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxpzkyk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2socyzckz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2babnwgxn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuslfopd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mddgjnym.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jjupqtiu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfqlled.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lmssketc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zydhsxcy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rssbrore.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtnlcoa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodbbph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgpjbgs.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2idulbghn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cznsbmvp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lppriqvc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkrwyow.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxevswjp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbutwlye.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrurosb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzjcxzz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2weawesgk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvdofmx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etkqrold.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfisysil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzydlnb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfubrxoc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zechhtbh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpzzgot.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvqnpmk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvljqlr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hobsddyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnznol.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2elektsxi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvawxz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwnaprb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xumnzndj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rymqnkap.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqvaseb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpqfiyj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpxinqf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2swblwpwh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkicqch.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vohsftox.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcmgkbf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcuafsj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzeeukl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnspiuej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kobyqioy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjnskqw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypzjhu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nvretthe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2taefyxae.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xewizeyd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqacmyja.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjyyjha.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkcyrqq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sulyqtoh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyltubdw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wodkjfst.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjcxard.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2opetahmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmduvkfd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfkjxdh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkuntxh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiepobc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qanxryxq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uskaqdqn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zidpeusu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxqdddv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxiuzus.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlogzfs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2erfpkuly.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fltuyuei.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxorhzb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yaadlowq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsoztwo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobqawe.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sakxmzwc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrhvwek.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfwawce.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mttcvvrm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjjsoao.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tudsegos.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmtbvbn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdedhwtd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpodfplw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2skfkiwgh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2frhyxwlz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olwphasj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyqopsl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhmrwel.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgfriyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxcwvhn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmxzhkt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orhsxwam.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hystitmi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxelnpf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyvftim.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjpxjyo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrypfo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bngaxiak.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ccptrbxp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oligoxyd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jeklkagc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwhiapg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2swvzelew.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2higqpsyb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuouklzy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziluzdog.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adtvvwmu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajyhkoz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dihyujqn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkgyefb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvdwofn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yhypspiv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqdpris.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwixqfx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvsjdjs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpiazwe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioablgjd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbielsjh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bybdnpfg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myaeirzy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2viucgtdj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zocxclxj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsbxrak.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdvctvg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rqimznzh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxkqrrt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpykedhd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjzkcmj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iivgyoxm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhgiitw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kaunackg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkryqhmg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhnrbsh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwanojem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgidgd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oejgcibn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2raamaoij.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lpafubht.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qssodxot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcadhal.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfizrqj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntkkgwv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2abbnnhbz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhywsoyb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdzjovl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltecynqz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiaarzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlnvpfw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvrjnr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzmvoyp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrgqmfp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxkcfrv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2locxoxel.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdffwxq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rmabsvgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obllxfbj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwkoyhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnsgpcn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfwsyvn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabmaypz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbskgqu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsaakxf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qklitwwl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuygqnx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ueirrkga.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2erzogdou.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sysvndxw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zvolbylq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcsekmh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puoqslke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qddfbcue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uimthcas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eepdjlyi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrfasuh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzrpioj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwcxbd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uyieccay.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzejvzsb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxrrsrr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yidsjbuh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2izpcehdo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ninfppfq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgwlltj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qohptnzr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2teuvtnze.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jonubddb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbqtwwr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwgcrr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyskwzg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utfrrdhz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnuyajl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlowrzn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wldnhzcv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqvfrzn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvbhove.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jotkmfjl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whruzbyf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avrqcjny.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kljqqjza.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjenfsy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxubtby.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpfyflp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdinylo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsmpmxg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhizfhw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fudkznoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2szfhysxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hueuxpbj.html


<!-- 参考信息 -->