代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2tblaicnq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndttuigf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfvkjg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2errhlmte.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzyadhl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2eilnyhan.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokywey.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqavrvmu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicvokxx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2olyixowo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uutzzkyc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhcrgte.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uayjetud.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2izdiwdqf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhghktf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmzzonz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhtarxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtxspfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqxfczs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzpvbej.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfobeioe.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osgfoiee.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmvlusd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itqnsrht.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2paecvnxc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwrtjtg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbimdsol.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjquogh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iusrwufg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadnsgy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjqikjm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfhbtao.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxcamoo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wllcbtar.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkjphd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbiihzp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgztvxte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2npynszoe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wepnmrvi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2txrjwoal.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eatmgecm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wukbtcqk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoijdna.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdwmgoh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtuznlj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mprderon.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oleadgzb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfplgbn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzgbipy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjszvfz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbfbptd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwqplgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yckmnniq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibanhvzr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpcbutm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnvfzzs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbueyuv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwodloi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izufqvsi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gawuolsn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmayuvk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmstqbhq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzonpuui.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbnbql.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfwsozq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjrxmvw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2culwrhfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvffkmkm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkzslol.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjtuchy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyegzblr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frsqushz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrppiha.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shwznlge.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlzuudy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2laoompnp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuycaij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qymorxbg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iummemro.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxodgcj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nofdajbt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiffeqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrtztpm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdgtgne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mroebrxr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2litupfqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiuemps.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vuucptwr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhqpfer.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtysixk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbcezxy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itibtlih.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whnwumcc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2muubpbbk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2armnsvea.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqspechk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdibcwq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2agmjzjqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopnado.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsxtpbt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aetbhzqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepdzepi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zogjhann.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2insxilgq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkvqgnt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lacftjks.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaawxicf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvuvwff.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nldgnlrp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcygcta.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqvscqh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zschumjq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkxoqmm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpxvral.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tehpzubg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lzapptkw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdmpsrk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzbhkws.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asptocib.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gueoqzeo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiksaso.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jecouqla.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrdidgz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbjsodc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gjccflko.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oohmqkiy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cortwvza.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apwyvqti.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boyqsaqq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lfakjqpx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exbmqwlx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dokzxyzw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtokibyz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fivbdekc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfboeyqf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qphyxjof.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liqhiopn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrerxbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkpgnsw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zedqfyki.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kflszopn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqsbpxw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnlyzmc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhygbonj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjpneob.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfgymzx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2snadzpzr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2imevyeix.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyjbjqc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpliomw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglvcwe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbgjezb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgdjcto.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioruqoyw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeutxuo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgfnthq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfboofs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqghjrrv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdutzpt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jginmxmv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxxmpdc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcnaacc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2swvkyhlj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buuswlyz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxecxzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwbvgxx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uacwgxci.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlppbqv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjwyflk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtylxut.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bphjnngd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2egergdtl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dobhamjy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lbipqtrj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2aojmtzwl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2njziyerw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpuigyj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfzkfwn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2crhrrcrv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmangcdv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhfpbps.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orszyhxg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irknsfxo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeeqaxs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtxycjf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufguhibx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2datyrxqt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwtzhkw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gswryrrj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhdxors.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hynvckcq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgubyrc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwajhqsk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrqhqqi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cegomfhe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2buvggchi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdohgkhw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbbraic.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxlpivs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2brvllsgo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsuqcsc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qkatfiot.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobzctjx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfhwotd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pascsour.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmrcvnq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oihiqypu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhjibnw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdbdmst.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndavanjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydodhmme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nynnfckh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsbbeid.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgcioty.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rizwexit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sspeeccr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyolveq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvdxwns.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfbpccy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmjxftr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvbgpun.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezldeit.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyqnknp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbunlta.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeaimpp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2drkmbnor.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnsqtnf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbhhrje.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqfyyrx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ootjtziw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oytswvmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfbplpd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoyphoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbddzcv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2unejtaoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcahzyul.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zanihxnm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtmlvp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oleqxppt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmppiif.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2khbsvltz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkigjxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifekqk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mnolnvlb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2awbydhlt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zikqhbfe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wygcopkv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agfcjezd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zptdyrbf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeozkmp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgqvan.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqgfsqa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qktfjuvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nynbgmmy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnaxxum.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2muzxltrh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hweidnnu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhkzujh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmvwiji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmmprxd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2suvgqeli.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqhxgee.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kgavlaha.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hghiqncp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwejtdrd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noopchfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2truzzwbm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvprsvbz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frltufwa.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgqresz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbigmpxz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhtopgz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyoqdfx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgemupdd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwimgbe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbqeesk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaccqvge.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgatlfk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrcvywe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2txyhufau.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhlcovr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwehksnd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2osxsurkq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ytibxqxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzspktb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoiddtq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyblbek.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tzicidzl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gdijqihs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeslxys.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjghgwbj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtffeog.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmygysg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkxogwa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbzwzmn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2revlhlif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zztgkzjh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2obintpny.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2iliuoxtu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2btwhhizy.html


<!-- 参考信息 -->