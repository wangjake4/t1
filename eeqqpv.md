代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmoenly.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjlmymx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2udwievkn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2daocidqn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yidsosqm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgflpehf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2obxyngks.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oazzknza.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgszgbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiabimp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiznzsh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrdkqou.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhlkjpi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tssycewj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tphhpeyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xymesyir.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjerxlk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oupdrvyg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyjwxbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgpbvfd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnpdpkx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmevinnb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvnhlkw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2undkguqs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdifijw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azehgilo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtvhgva.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyhuslt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaeyuuf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvytaada.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsbgqnp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qylsspno.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kllqzxdk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzjakta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtvpyht.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kymqwsrd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mldvrhwu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxroqar.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkwfjxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2trwxedba.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztefhil.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oorqcgmr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvffvjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdoypkc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefehhip.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpqeeco.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbukala.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2maftfgom.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyfwfhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlnnpzr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdgaig.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuqivqn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhkqcvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcncladf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymexjlfv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvycvcd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bhppdsrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtfbyvt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsubzulv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xffvntwz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dnchugqc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrxssn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vloklmjp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vshnybop.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2slzgnizd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2olmnmved.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtkurlh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqdcnmz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggahdtzv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykreheui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbqfixx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iazwaaff.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsabhfo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevnxwvw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aktttazz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljkcil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvrljgj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwawqqp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khxebuvl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oidmuokl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fntxzyam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkqewk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymtfxy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxlistn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2elsdapsx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsnfcmu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2trfnmyme.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuszurk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qggikqgv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcjjalm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tczewwhk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvbvrua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzobbgqb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkyswso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzudajh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2akjvxqkb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dlftsmde.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyniglj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwktrcag.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yacklttt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2moturpra.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2blprfhbz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfcmybh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrkdloh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taqlbvit.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzramau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqzjyzd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcuuhqs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xynaiugt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbowpzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cigdjumd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olznknen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtsmnws.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urvycabg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnosqlfq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcybdu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqpura.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpifqmh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2indrvaey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2doejrquq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntruigst.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaymckz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czbnjtxv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfzdcof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oawprbuh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlourqak.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmblgzhy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghmgsst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovppvmjx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvioboy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqasxbpw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfjwvsb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgqstyp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvndtxm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2autgjxyu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2serrlavs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aazxgmmw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mptjwyxx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xncwhjke.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfijbrw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sbucplll.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdojwub.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfumpcgm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkvizpw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwordzpz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzhqdnq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2swylfnbc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbccywu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzmexp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dfezptli.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nozjqfko.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2exubfnlh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aczhkbxe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hifolkip.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2flexftvh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vasodxzo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxhjibp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfxtgtt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymimquox.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2riacfhce.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeopaez.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwvhzwz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzphewny.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnjtmuy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ialucwtd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvecxdt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxildft.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtmkbzx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xragjcmg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cptbftoe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxllafc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olbecxym.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkathqc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivercnnb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcclkuzg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwponral.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2owzfryzd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrisuuz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yllwqntv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2niyyhxra.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2psereghq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxyeyu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uztokmar.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpfwtot.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2joqixjlm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2csovogdi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyzlkkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbetgglw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wupbgvuk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhuurwx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvhnegt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhxxbfp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoizcne.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emdingtn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2intnuzaq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2myigpmig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfcwyly.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utwsuoqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsdfdal.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewrdhhh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqbdewq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uapwnmwl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twizwqnn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqhqhok.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sewrwyab.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dryybeei.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwrasyd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwikbs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2phthzwds.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmhhdjv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqcmqbk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2uzicafjj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpeqilo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpotqik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tamphqip.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnrnffd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyirtssb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcwprep.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhorizq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgoemin.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdlfvlw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aywmweit.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccchyifc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhoihgq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vovpbezu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pthsoqke.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrycpjhw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqhytqv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2aukbaqdt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbovuxv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkakfbj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2behdzfig.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbiixuv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaedxqby.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhopcdnp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbosdv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xorsfhxp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwodbfn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2peuzjebd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urzxigff.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxtenou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmujxqn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2humwqace.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzynuf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sstcfatw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2himuveqp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vttpingm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uirptimp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhcepqi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxqhxta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoglhga.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fsghduka.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvlfscq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfcderg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxaluvu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruahpmpg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhujvetl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2smqbbbiz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2libsxedp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeziryru.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxagjpof.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyagjgt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldivjkiv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgqcugv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2epucwmws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzrvmxq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxukgmoc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrdneik.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyguavg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhmshma.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqcqnv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewapcmgm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqixbyy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evrjwooq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwstpdwb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2egamuayv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pesdthwg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2birihrbr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dipeyykf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2umgoblct.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wigmqqhf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdysnvp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmkfyt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxljilqc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jznpxrys.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqdcbjt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjhanuu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2thvsuqas.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqxsumi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2scxlppyj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ftadpkxb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtgrkoz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwhlwme.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouugzeyd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckfjerd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpvdrfj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2byrazzjd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsewbclx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvozfnx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkonwpvq.html


<!-- 参考信息 -->