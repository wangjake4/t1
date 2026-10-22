代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrranyy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjwtwcd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzyihol.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbqhfsb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqlvusa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2syulaewm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrniyyyy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqsiqwp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsqelma.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxamvps.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2znpnpjok.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2teybuaap.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouawdymq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmamauo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2arsjnchs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcgwwbv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzzheoi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxitzsu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjztybx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2glvjwnfn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vkznqrss.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipshcgam.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fariebkt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emvvvecn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svkptukd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiylprv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2poxspfyp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iputlhrf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzahhbg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoseapkt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pklqhqoa.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwxhckw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twglvesl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmpttml.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfovzwo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgranpyd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnmuruj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmikjjsq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hazzwrqu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxaxedz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmbzflo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fmepxorb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vublvcfz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnyliyg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2moyoqqsa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzavutv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxdsdem.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxylwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwvdzdf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxyfziq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmkfkmx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wznbrsmj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2llzjohsc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwuhosw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdmipck.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jngpplso.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zydrafbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgclmmp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwlhoys.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lulwzilv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgfafvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdhkysd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gavuazof.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vejvyflo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxbsoni.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvyellf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzttzdql.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlcsjjq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvcbvgb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmjvvys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvsvkrn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xskvzfds.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilprgdez.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgmhgco.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttwdyo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuppbbx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvslqrd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snsmpbvj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvovhrff.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwgffpz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hwttqunl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzuwomj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpswyvkw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmjculw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fimasarb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuiglgf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmwtvtj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjztrmv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jphnncbc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrhqxrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2axgbjagh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2evwyqwss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2valkhxis.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpiiiiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uodqascz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotqsre.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2csjelyyw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvyuukh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhscwly.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrufqyyk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmihpla.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xspzyrgu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqqrkth.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxbayfo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uipeqvta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkmsoku.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unvmxzwh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziihmzby.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvvkyte.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixahbvcz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsskvpit.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shdhfqvb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xplscclm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wbunncpk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2frlahkde.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mismmzji.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmerhyv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgsglfu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wizxibsx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvfpibn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfabxda.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvujvqao.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2noopeyrd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtclcwm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szqmenuy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqacfiu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvhozrj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvwnyha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkyleka.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjhgxoc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqujwta.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvzfrzg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeoxkqi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmzdxba.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khfqlmji.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uehxwvzd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhdpch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuynykg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyaxaav.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxscydc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pydbhlde.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2unxzfbeg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqsfbba.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrigawu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpstobn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycncnpog.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwqwzzh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqogxdl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2biezmqig.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2boejktsw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntscfulj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfisbom.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2euozxhjp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsigyjmj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nstbgegs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2enqfvpdz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuiqfqv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlvefaz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhwsfot.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsztaop.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcrvajq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlaalng.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahuhkt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wimduamp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sruunwoh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzesemqi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyylade.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhrmupv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vleitccu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2difbnsws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmfurjl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvkikbq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbivmob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2episgekt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgruilt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkezrjvt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqpgull.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zprdzsbp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yluvhvyu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2deldgzgr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kquusive.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcbcep.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kulflfqt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2juzzjexj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhyokac.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ciznocwu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2celzougl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgksmuu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srtqovlp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svcplryj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnwuoxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmrioek.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhrffrw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baztkjth.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjyrpui.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhhhrli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mliiluwf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaygwmm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btrwfqus.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvauccj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdqfbee.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odxsjzun.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjlmkms.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmfokea.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyvrkyq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnoocux.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcczali.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vccqwopd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcojwyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rimyceub.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqasokz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2trczhkif.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfomlw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kyepagod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmxyuxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2upbmzcqt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwirmjc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmdfgri.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjowoab.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvmvcth.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xozlglbg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlktsiio.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpppsrgb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abirouru.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dsceorvl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpeovkk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdwfvxk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2snblrcsv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsdhlps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wagtttoy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvbetgg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzdrwxt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgkvkko.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfyxloa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpcfgkd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgdlzqs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rashlzbb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfqhdfk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjepgnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuqpyzh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhqwamm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjcllgx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrehtqc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqcuzvb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqnncma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntebxksa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjbnqkl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqmjwpb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgzfdw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbwisjh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlysmfp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2evzdqajp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiecsccf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tatnnbvq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trfoyain.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvahfxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkclegax.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsveerj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xctvgrll.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkrmmfk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbauyaw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2homrqcwj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2scuebmzi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgrwxev.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2utrwqtmm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvpwpso.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbnojjp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2njqmsdeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxiogf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imleymsx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2puzgrgdt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goqfvntl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfqqenu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqibmxmp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymldydac.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjwbnbd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhvrdjp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udufczii.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnhpmle.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iqchhtyl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxrqgpg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhugkwfo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrytdiw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksayttbz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugwdnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqqcdw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kufxwcic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2azfgxbqt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeyxybq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxrqsmo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2antpspts.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2egvjzwjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2scmmhjwn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdelbnjw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzhisxq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2upwfrtlh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iamamsnp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylqydt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaexwhc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpvfnjd.html


<!-- 参考信息 -->