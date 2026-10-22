代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqfcvmc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arstqdbw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rykhmrzw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpvvaqa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrllhorz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvadtqkr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrlirb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpbkcjw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmkzbtx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrogmiz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2topwtdxf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbtegym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiocwchy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sordopbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxacexvj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xifmibfo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsjiaqh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgghtopj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuapdoud.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doyktphg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkbucmn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tetijabe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2txphyhah.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyafcru.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2waeosouh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuevqmg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2entgatqd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2noxlrcxc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhvvihc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2idxrtrnq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbpgegg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdztssw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqcvfnc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsosbagd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzmpmus.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzxcixs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoefymo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoriirz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mklqxwdo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gncihdlo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yagegeqs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhxldka.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2erpkpcjo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xafrhrdz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tukzaxdp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2efnsewle.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmnpekt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvbcrwq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqsegb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2arnzilfs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfsjibo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cccqgcfr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvtfxku.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bznbslol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqiuisl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bakeztts.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbsvrdz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luaijkso.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiyybqv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgklakg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoorbxzu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyneyug.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpnyrmx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrlpysg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zokjrzaf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lexuxjwq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfipmvy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2geqjgrvt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxuefri.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nusnxzas.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxxmxr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knmsntns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wliylhkl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2odwokxnf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2piyotkrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odzpssgr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfydxoho.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2heanomjp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2huqxjinj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2waplcnxs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oluxaugv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfxzvgt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhfptmo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfuyrso.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbakiwx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmotwkg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgygvjq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbxphcx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ildvozuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsphoax.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwugsssn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iawyufrf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlbktjd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoiehyc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zmklepnf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ynugfxmz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpjyihz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpbyqz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhpadig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjtlccn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvqcjwm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yareqwms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhgbdfh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhfamak.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2arzqgaas.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evnmbjcu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbtgous.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kelnfiej.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgogxdy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2izywqvzn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxosmwl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seyivavx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atlhqnmb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2djuwmnal.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsoswwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brggpqjt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlgjcyk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brokulnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkpxowo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lphulkxb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlydsbl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsetgab.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrbjhgc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2psqiwhrt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrpmzq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdaqwwo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzpicoc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2satzvczz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjmgtpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnkexzv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagbjen.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2opgyrizf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiihbql.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camnslwn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtnjkni.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhmycue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2shvvkqnv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oranxsyr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgosccdg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2niskazhn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2orylemaa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plwedscw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxaeyjv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuumdpx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jynkywcm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaxlfzc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlinkai.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voklkzyi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaxhxmb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvlnmkk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alnfrxgr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iricviza.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyclrnwg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byomnqqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbnaazz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kchuscbm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2plijsyie.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvllxyq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfzedp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovsukb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfannbp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2msvsxcdd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iadargyw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyuaexw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhffqeg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpyxxds.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdoyjhd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzsvpcv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwxrwc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwfteya.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnanvozs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuxkuqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxwjrfw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvovuov.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saucrpdc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vipsfvhh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qproscwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylawirpf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pekmzhgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdjjngh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqcmzow.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgdvgcw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcjxhgo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejnzgiy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2chwvxbbe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgnkvw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdeyknz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2onnjfxqa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hooolrhj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdohieh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkwyfmd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nulbnnfv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zpapfmnu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsyqkvv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaqlihl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deeovkna.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkruoyt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaiktfj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxizyvhp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2empbdhww.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jcybyery.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygnaein.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wiphiwnn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2skzhmlvj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbbtbsj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrhgorw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcteong.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczgfnth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgcsbho.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2swzabnya.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaksjqyk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjurmwa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wggieyzg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvdmicd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2edpitwnc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzretzc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2odccncbk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxbqta.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqtuss.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sbomqdob.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbftnjq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbijrjk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iplcqoyo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqyyhfh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2upitmmzr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzupxexg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuvtxle.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlkicdx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xamwashp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2noliynjg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kukuhiob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lysypsts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zuljakrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaytpywq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvfrxgm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlafkaq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2duyvyefl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrhzwok.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvbosj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xyttuxmc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxglmnv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcegrmdb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjylhg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2emhzetrx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vodcxvwq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lcievmym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2reaxxffa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdpsnxi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2swoabziz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2subtegur.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjclymy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgchxvz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvdjini.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwnzoqx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesmbpry.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oscejglo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2isqfnghn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqagmev.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkwjxkn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnrpimz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gptcztmt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalorbbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2regagckt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogdjsad.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzsandz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqcvhre.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dachahjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gthpnexv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwrjsvl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmgriid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eobycngl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjjtrkz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfweqwri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxoxbdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsuihur.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzqtlns.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzheldp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiscbzt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qiynsbud.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iykdxnch.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxvyugi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqgukzh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aynplgrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfwxxux.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgefevwj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kporwxlz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjwvfhl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfduhiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whsosqwi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iywkcgfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twcnglsc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvalwmrt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2doohylxq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zcezsfcl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kttvhhhk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nahulnpp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnokzli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiwlyax.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrherwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxzxswo.html


<!-- 参考信息 -->