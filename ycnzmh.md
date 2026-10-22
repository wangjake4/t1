代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2onojfewz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icoguqny.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlwhiuy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnvxzwp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvuqoqz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhuuvjs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxgmebx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmnabrc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxpswiz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrtssbq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwctxe.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khsisdxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwtpbav.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeetnzds.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfgcknv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oudzzijp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2znxjllcl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoicmtm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsbbiek.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gswkphgr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dswmkspe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2owqpodwt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdfvbil.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaszapel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdsamhq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2moquabke.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhjfyeq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwddnjn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sprcpmwg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatpyda.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpjvzah.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2svareczx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiwesbo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzxhfff.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxytzstm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfeodmn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvzuwf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2meamqunc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrqobeq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeixrwe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rexktfpl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjlasnv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uupufeuq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2exbimtkm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdriksfa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttocmmx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmprbqor.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcrtndg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kturntcg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqlszqt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqnffou.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2heovtkda.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ienfzlux.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2buanqkdo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfytvzfl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2afbpnwom.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiuccky.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmaawcm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynazwguf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2byqqcfed.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vosaeawz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mootlqry.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrzngus.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeslrpc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwztcdw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tnybxxoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyxseoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqydulnp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgaggpa.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hopknsaw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2izjpbgqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znkzdmfo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgtfnn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aetjstcv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gelooitz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsptcfpj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hymeyibp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usswmfgk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdplpkv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgrnsxm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ryggozud.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bndokcmt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdfbfsn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuatvmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzodjrs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xopdxcgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gabtdipg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrfstl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vubvtghs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gayplijz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjlrele.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlqvfbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sugltuvd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwqmay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwsykqd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnegnmg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnkhxtx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxnblbg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xagunqub.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlitgacs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htdlveyc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfddqbzk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgymlfs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djjdcvuj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlunvblb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2waumomaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2limcpqzg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldkjrpj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcwhsa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqozxdce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdianmzg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2orohivsi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpopffz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2abaspibb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghthffhy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsifxggo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoaanne.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtprsyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyedofz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjlqjcm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2phkmbaag.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmnbvuz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kzunwtwq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2btxlzeyn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbviqji.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosdpkts.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqozmfp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxonklsa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwkfsek.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2resbvghs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kootdyih.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvwhkwc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2murmcaqj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoicficp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiamtzv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdcouo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlswsfu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhfgvlw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhojqet.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlaqeqm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhsxfcz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmwbgxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvenlid.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyydloi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fihkfzbe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjwyfhw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oqihdbif.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htodezsw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pisiqmfn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2udktcufi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjfnaib.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsidsaa.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtmuqsb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oioafkzg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzckeig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2auaqucir.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nyczxxog.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbbqmnj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwripvxv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jamkdvuw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlfybzk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjmhwjz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toitrrui.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqncay.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohybjtto.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdghlubs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znizpilt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxnckgr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkrkids.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhfopi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzxyyey.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmibjtk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wafrtodv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrktrexp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvrbbzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaklign.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuicbtzm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wevfsgrg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdjanrv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mgecatte.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmnkeoy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2atdzitkh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsjzhod.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsviwqo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdxguau.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjlepuv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sadkittw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtgawtf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfowmxfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovdwlc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaamyun.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbttkfna.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2njwrnbap.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gktryeje.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etudmylo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vncxxyda.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvsxzc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qamyozqj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqmvkhx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvtlecw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxscgez.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbpswkf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2naukubct.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phgqolqt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwulmfh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrhxnk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkhtfms.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uxivkdtd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtwjifw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2axquzcdz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gydepxto.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bnufuzaw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaztgin.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjjexwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrkpqsm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqoyrat.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oajiuvey.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znkxuhkk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhyoipq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lnttcjxi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2prltsieq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdaghoy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quducjlg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nygjldif.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gvthhsft.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2girlfkzy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijctvmb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2frlcryyr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kkujhxub.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdttncp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdevane.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjavdcn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fegpheie.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnmnlrk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjtxapr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdglild.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2joriiodq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kovysqwg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxnrimp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrmtws.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutogik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crgedfnx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlnbbot.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sskbkxzp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxarbqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadhuge.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oijfspiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuilqvw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzuekge.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyovziu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjxqalr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqsaabg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qliczniy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aganfxsb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdbugru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnunpbxs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoorpnav.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgwfsz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hknwvhkw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjarzmn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqdbhxi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pymexgje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxubetck.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtccwzoy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnkodkf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmwvncu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbeoxjr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjforsez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbfqbvr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtpytxb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gebgyabf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbzqwht.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjctity.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywidcdgn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnoaaj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwlmdkz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjwwfdn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzarhhh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2galdorbb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eijjbeqb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zulfssmi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyaopub.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mytageln.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwckvsr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfwukcm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmibeki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpspmrj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tngwjhzs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mwepmfgk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtydxxdk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rkarptna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2msqvwfgi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdcurpq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2imzgawoa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aotkxovw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpsaoml.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjnndrm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cueqsyrs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkybdtjp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmswnce.html


<!-- 参考信息 -->