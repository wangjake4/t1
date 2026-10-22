代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvirfzh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aavvbxaf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpdhafr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwosux.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2khkiwslt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2erozufld.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfnvvlh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcwdjxo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzonktwd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbcbeet.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqrpxfy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzlaayu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzatawvp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2svmcpvgu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjifinb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfafrjxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2smjmrwlf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tndcqhyc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpbfelc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsfxxwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yepxtrha.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbieqxn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhplcke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urxxqqds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooivmzey.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmbgkts.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibigwll.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edlxgdce.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeoannx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2femeahut.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbanmozr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mppohwqa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xordtiiq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlbycke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdwiuop.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2caxnqcgc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2puetiltn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iixmogne.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrofold.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylurefv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvvznli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aovuccsw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pabysxvx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqbtdxv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovckome.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fslalrhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bowfnjhg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnwldad.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrsoxy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlhapmu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvekwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbztklbd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsycgge.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfdpfoc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2twderwpb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxzbnjn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2shhcoprh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhprnyiw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lihwlblg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eswouakh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sthpoike.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fihtbxxp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nncykpck.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkpuung.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxvslb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cyidfyzg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeimagmy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqscbs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qapkqekf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzuncn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cynabhdx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhvahcg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiubeug.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgwliwo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhwuhue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iepyeoir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whbmwbjs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxkpyxu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgapbxmp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmtpxpk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtnjxin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjccvovz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxilqrb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtzztpf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcwnsbp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnbrxvc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuklpli.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwpyldi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dranklzb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dufphccy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2omljepbx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2encqmwec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jknwgvgk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2illjqfdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbyjwtd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkwrerr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgkfiyz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwfbnvz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irhbgtxc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffdmqy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxusloyk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdfznye.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqjbiro.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sslczjcq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinqjwn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2clucxxtb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xapfsrrf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbmvhzm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuglvdzn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukpuvb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbcckpi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjkrepm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apwkbmas.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrxhxzj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2twxbfbgk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2otafgijy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtotaot.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qylrqorm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhioghhd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoplpif.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnwbiyv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhfpksd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vcauzqbv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrrroh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mymbniuk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chcqwjes.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmkfkan.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knhtyxkk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2olcrxudv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iscrcnbv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypprfivy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wsojwvjx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2naosacpl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgavwwg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhusvxl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yssedpxj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkfktyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkszeer.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnamydvl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoqpamb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vmazoqmg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aywbcfic.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxukyhl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyiphlt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klgclvxu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnocerf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ecllfelf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djwqdvlf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxkiyjx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jaahhyru.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hspnkumv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaymfhz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmbckie.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkkubew.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2togkporq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2drahsvll.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwxozjl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnfdjey.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqouavg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yphujhdq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqlzxnc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mitimupm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esoynkre.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asljzzzh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rozdmcxf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wklayfqz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjfawte.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjdfvuv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tofrmlxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yydalbih.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iawhgqao.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtxryfz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipupwbm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqkuqzl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obofbihu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juflyeul.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dcritvsi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ippqcluq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itukzifs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gigaiwdc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itznfsyf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ansxibez.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2aebovmfd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pujojbif.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ycayswlb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2owvuhoho.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kjglrzvc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnatede.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcxqycc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcdruhb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpqzzir.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2joiasrkp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvqakga.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuucvrar.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzljifyk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqimeph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eakqrudm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjvzahn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoavyvd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkdgssm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvouwgcs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvmhlj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agqtjecb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhbmawy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvqaxau.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hqseoxxq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pljemrfg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnrwnix.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pagezvoh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtssvul.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2punohvsu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2uafyuuiu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ksupmupw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyrcdte.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mhckwfri.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdthnns.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwvhtv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtgfeqd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfntvxdn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqhvbjj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxghssgq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxcyssc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvwjpuo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlbgjp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqiqkww.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirhiajj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkoitsl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmqyktt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbdbgt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qimibabc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxgaqgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jblwbkdv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahokgfz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjagtxi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jddrywgj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjyexdz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyysiic.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbgszcj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cdulsfyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kiblhigd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qfikszyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gilnbblv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pkswkejq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqtaxoz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqiyni.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszcfcx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwxhcj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtawbwgs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itvyilgd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqenpjd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcitjed.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2etqoinez.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtukxrzb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhgrkqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwvlora.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafssxhd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddheryx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrsoizk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvsami.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgbzgrd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rltcixfy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yabgmnib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2etyimzpf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjtlgx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjwoaap.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrzfjzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2unxoqokp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqzqtw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bljjkbjl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzebceyk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2taztqmyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txvrayyj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsvnymb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tewngjhr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaerifpl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxapjll.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rghusumx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrbqzur.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbphkmj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmtvewk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwrszea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgciawiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwouhkfl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzzgslf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuncxzc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfvmysd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sztyweob.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jstpyits.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2brfmeawl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2igacquye.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2isupvadh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2milqomwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xryexxuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpmqhil.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmluycd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkgbxdi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtlanup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsxyvwp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yntszcaz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2muyolwnk.html


<!-- 参考信息 -->