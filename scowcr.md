代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfulhttv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgqejzh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqmorh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkbmsos.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwkkzak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiglaee.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rswvfcpz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjhjuao.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdwxwuq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfgrwbn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gicfzxiw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onafgheb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2focnqpms.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2upaxsvye.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2llyknseb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvucbos.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2chibosri.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2udhpvbpw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmghdws.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxuwems.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrmjpfc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwndvop.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yotudzfv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwhucm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrkludq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhinit.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tarvsrgl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvzdtsh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmikwkqx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcoijge.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdimtps.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2esumvdcj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reyrhvin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yullrcjq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhzupgp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfitpbv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjdsoqh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddupeoth.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2godktcqf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswqlott.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2duxssbck.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgidpi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvgdbdt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2smaqcysv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjyihu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuyiszi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fycleqgg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kakucqko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxiplbs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crleoyyw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpqciew.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xanagqyl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgdttzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzrsmz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hismovlq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qguelagg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzrenuh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcomkibf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iblnumsq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaonvfu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dqozpqln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzdklxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2snuxabab.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uisoltao.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmrdjiy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsoaqpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttguwyfx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlluvmrh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghdvhw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyljehmi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2masmxsdg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkxpmgu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnparsi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtftwcw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxfhlvr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2letxjpli.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdgzwlo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vshxepfv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqsrrfn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwcacnb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgzsymb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsldgfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gylvlmne.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lullnfrt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgqxbtg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2njmoixsw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2olxltvza.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnyzxng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnqpvjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzotijs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpgzzsy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yooqrmzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxopwikp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uxomkfda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxahpdgc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2waklpwvt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qckbkumx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uggqadks.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fekesiyp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfqhhxi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyilobn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuombiap.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kapdapdq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooedhpnn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2genjjwdq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2djsqvdkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwjvlp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwxmqp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btuktora.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woqzazrx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hegdrrni.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqprgsnw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuglspre.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2opqbdais.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvdnjiq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slpxcqod.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2scsdtpyx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2meskegjh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpfylcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfwdlfm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzgodsi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hayhvzns.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgcotwo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxixuga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyjrtdv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umhdwqif.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hczknynt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrvswtg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkukvoib.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jymqlagp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwawsdx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxeewvx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnbkfkz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsnvceo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giimysva.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhrnoky.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btiutvqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dramilbp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mavzqqif.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdrhwqz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzcocss.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlofsgkv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glkvymdm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oucugjtp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmdwilx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvvjkda.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyhmwgp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2caonbpwe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jigsctdk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmzklqg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2twkifucj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkekjtcj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcnuakn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfadpgfp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvxfgqv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpphyiir.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzhbahq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzgdgpq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgixywm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgosrdt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxflgaav.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvncgp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iochukjj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkamquf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycocdnxc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bitligbs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsxtrds.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2smrnoiqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnfkris.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgbmfvk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnuxsog.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcktrnka.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafptlqi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsvydad.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swzavjho.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdgwjuu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pupnrkxv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfqraro.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnefbtk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwqbpne.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjnahzz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyphisy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcjuxmj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeujepr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ivftizjm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hromstoe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eokpovqv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyuwzqh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfihfbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqzzwac.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cquaiqmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yooslfvc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrrxycu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbojldmf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmpwxn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nninjjyw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvvbqce.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niedzmvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqocdigp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmxidp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qslktmcs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeaeeiz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pumonhhj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqeabhv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwwwhuv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdpmgek.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hqumfuwq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpexcsv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgsjgdv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmxtlga.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2taevlhvr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nhixpyno.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvqpeoe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdybedqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2urkcmpjk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2poxkgzgc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehksywju.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoypynr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qefnbqql.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2acnirvwk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvrtywi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdszvwr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvctlcbg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eolnspct.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkfgmba.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmdhck.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyhheet.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvvwrgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lypksubz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihkqvkc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xcllflgy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmduklx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcfxkss.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfclvzj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ictckjlg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyzkdvo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mycbggbd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhqxhhm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqmkzee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bafzglra.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimonhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izwxypev.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdesyxj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdulvyvx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilphrp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlspckhp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxitibs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaqlitt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tytczfqc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxivcuvu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrooykqt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kclxagka.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhvfqvx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhntqaz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooueltdz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwwste.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpxttrj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnbrntz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhigkbdj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzidqrj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkmovov.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2easealhb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fryprwyx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmewwbr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzidjrau.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbtnmur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbewmtbq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyybtfg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaxnqkb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgylusnz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhatsgn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mngaiefu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhonofd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwvigrg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpnwfwj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2menbokeh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alqotugc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrlgmtt.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqdxbbf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmifjse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvieqqoa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyirdwg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnmaigo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zczwgtkr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrzbhfk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dbotavev.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbufivi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgvfpts.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2csblpanr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnahzczd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2quxngogg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2plzxjvdf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbzarfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2csivqpnj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnfwlpu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dmselqer.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfbyfsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrkenmp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbhljsr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhoyeyq.html


<!-- 参考信息 -->