代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2emckbiju.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdqgljy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmewuhzh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlastjk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfudqks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yclgzjbq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyipssb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2polerdhr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbjark.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbjbwgt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbekccc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfnvity.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyymcnzs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyuigoi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mitrnkrb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbosnaq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmiahtn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2obalelog.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfrxaws.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjkjinf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkrfwyk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzpqejk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omgymztt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muccltpt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rclkxwmo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2obqkkwev.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypspips.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbympzp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idvxiewl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmamgqiw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuhbqqj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2quwpqmth.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egcbrycw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2holcbklb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxatiw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvoxfjr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvjnekx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyfieiw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrfyaxr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2irrtfetp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgawgqsx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhntxtlr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxmqdf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaipftm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyadmxyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jduhekkx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrqrtjq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2owywhpko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2derbasfc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrqkaew.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nflmuewn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfwqebp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cngrmdwl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2clhldsrg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2munjyfio.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhhajoy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrtwjup.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhosldg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbumifa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbquvld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmckysi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2msbeqgbt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2artmmyfp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boduycra.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgmjiat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2czsxirib.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhuluqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxqlmzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjppevn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oraoiwyo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqwfrtv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkeqvom.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzydauc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjhyeq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iabgedmz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyymhkg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlykrie.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syvovqfr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbpqfng.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crouqjmi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrohsjf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpifkihh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoeeizq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfdaxsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqdwygv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlehgzr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gncxpynr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvmhwbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ecghrazn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhhivin.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtpeopa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlkpulm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tittfmuk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgzyrus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rotdepmo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvevyfqu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjzavtm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoyapzg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjivvacs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazqhbjl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxlnebi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmottvv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqjqcmu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdryuqnq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htixddut.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrzafzk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxonpohz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azlqricd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgadlza.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqxcrpy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezjrnmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkfgaxv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbkbkww.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcxenwb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmmhthu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrvvktd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvurbmh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnztmjh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceazdudq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2olkesyak.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2psztvmuc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rualdrvf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvsmjca.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2epnjidbp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtnzwgz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbipsonm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgbmqzi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeoqpqb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aasknrms.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tygvynce.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwpppek.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwipqnc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvrtrfv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpucsfos.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibuabb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxukzxaw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxawunl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfcwoiz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsuordm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoilgxd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqyefia.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnnmnnb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2harebabt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbkxlba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bysflftz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkfdouy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyvphzs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfkazcm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oraflktz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dukavoen.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmhsruj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxfuxfm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2enyolegm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jinkpwnr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imeimsui.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsiursc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cefuwnuv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzybkvt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2apgsyyns.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqlegud.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiksinzm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwzwmd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrabtysf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wieomfrk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnkzxgz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jthaedvd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcevqei.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2augeqbro.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmbtyko.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yazgxtoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbasjtw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsusaav.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgcjzk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2galjmrew.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpwvjbf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxudodgh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqndctkk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcrustf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usxxixjd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwoivxk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvleorr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oklzyjph.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfhmrvi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vopzsmyc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wlprmpef.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yobwpxdc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvinqpc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpzvpsx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqdzzrs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocgamrk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralejkyx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2evhmjstt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwflvcbp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nueirbgw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hejopota.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2geohwfmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfolscg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqlgro.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unnkuezx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxdteng.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rledntny.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yeotwdbp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bertnnup.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlvdtz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbgbkgu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmxnlta.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2totktzgy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqnhalw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvnumrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdijkjy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttumxvpn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfaullj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zutbeiey.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kofymakm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yctcaxrj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqvvgav.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyaotrq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzozxmxg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oywghhtv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2phxjowac.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmzmlai.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iocneoem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kblrzbwy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgphjuy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmmrync.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsniykzn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntasvrdg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtobxqt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2snrappia.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnybrcnp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkdtbue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jduhrfgg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmhpwcw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhxpswm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfenglx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmajcmp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwnuese.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mnshacpv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxwywp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpztaqwb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oewdrgia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anxsggrd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuqcyza.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2znremgiq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwutkxgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gspevyfy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzbaow.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apstmhln.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywumyb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2inihdelf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqvwsfg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpttxon.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tizkcubj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstlewkx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvacrqz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwrpfze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fplfposf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujouhydp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqrasht.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfyedio.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjtrwlr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2grsgyfbe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjjfwr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2idlqyvva.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2grsjvmpb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2takqlsnh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqrsihv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gimlewya.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyrfhaz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfekrucy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tcschasx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anomhiny.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxokrzg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nigswbve.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agpyfimq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiecgaj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lewdrmgc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fazgutht.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atcrhcnj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2albbxitx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efeeahpu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uafhlear.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpyyrfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkvndwd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjtsgqk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2agggivbs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atheskuh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmfnnfl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtkmazq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cluaodcz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bbotjvoh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aazfqarm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbbobgu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmalars.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhlfxdy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2otiyfwwf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxlcqvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2atazslzo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkamaijw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2inwplklt.html


<!-- 参考信息 -->