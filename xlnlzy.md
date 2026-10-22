代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mefeenhs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmiaycq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqvbcqf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xadimsrb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqpkwhj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peoieinz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqkjqan.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2peedfemn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzktmlee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvvohmp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuimxtlk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiozmxc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehnqufq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eexeygni.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ludakyvx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bspoufai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ninwomxl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptfhlfs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrrsubw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2trfdxmco.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2saylbxnn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzuflwm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmgfxne.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhmkxno.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgyyidt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeafrtza.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwuheez.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhnclgj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjgjgqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiyaeri.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhwkckt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twppnebz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpxkwzs.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxujias.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqwpcex.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxsisjs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbanpmas.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suojauju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpqiczn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqostrel.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpdwxpe.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdutmj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2engwjhqo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqctldk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpajfxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnzezeo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2avaepqgn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhporrci.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqdhwrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2atxrjifp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugibcgnu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2udopbakw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxacspex.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxcuuz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfcoxoi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jromxpae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcubmbyh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuhxdxv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2esvcktmh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxrupwz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lebpferu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryslotez.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedaeas.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2holschkn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhitgamr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpbtxdo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2injmajsp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuodste.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqntwnsc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxyrfn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoznesa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbkgzfa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onroaczd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwgajrx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfffral.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsftxeo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2newbtxcn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjjavhe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sinprqni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdtrlvt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omatxilm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqatzvz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2meygvgda.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcegiwmx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrvpbek.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lruqdqfs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2loeiohou.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkmfwze.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwlvwhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yafazkjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2juzqovyh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xvucxwgo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2muzsczso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdqfsii.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoojavsi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbjfkkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygllhjip.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxokgis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuawlljm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2goazextl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vozvrdqu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzcjkhj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyzaook.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxgatec.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpesqsw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjndtyrz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlffjwh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaahbfmd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pubngrgc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkayoja.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwafgdlk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgnvlnp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crwzdanb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pupdnmbo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysohmacg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmftodf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcbffjx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2reoylord.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycfkqw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrafhi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djtalobq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lemufvxl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2axerrvdl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aessccem.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yshtnapv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozumimao.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lybrcyrq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dacitrpk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txezfjri.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwmnvyt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrzpjpa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txrcmral.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqlgtlg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ptssgpat.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skiajrsh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfdxytv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2izdlipcp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xavgltmy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khnovozk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgckxgf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzvsefd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkxmzou.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxopilib.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xczcrixu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2egpebwra.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuscvzy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juwzkius.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbagtrd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaocrdl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsuxvsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sctsgjgw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnykfyu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxassslz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxggmnox.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgrtavm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffcxpl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2npohifov.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aoleryqe.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyegscl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qfermjkh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdjtvnz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjzgwyr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjgpwlx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ojauusfm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otqesome.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euqxwqpd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvzbmzi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emqbuqyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnkuvlj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzabenna.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcamhesb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nliorcks.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeozxaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgzrygz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2crjxrmai.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orsbzyvs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrvawvt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgwauwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzvmhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeimxaun.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2egowrdps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaraoffz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zyntebvw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiviknw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjxftp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2prchxeoa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjkxscf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnthpf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2domuejou.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhonxzl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nxewzyvv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxjfywc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwmorlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjvtnfe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlsxvdo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjsqbca.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdliwcjj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eafkfaov.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtoxwp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rbclihsd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimkkwrc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scavpcvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhqohqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwonpqzz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefabbpe.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uldstbvw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjryxezw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prxayyod.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipimjx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2roehwpaw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpvgfox.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2walhwhxb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mamjtkti.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjpaieh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnneccka.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2odjjunzd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2khcyvkzu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpnxxll.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zdapzvhv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkthyjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvskrxju.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yilsxmqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gohahscj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaajqbr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lszmzfuk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vditwcff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkxwiiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hehhxmip.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cujfrguf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbcbrtp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2twchrupd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhuwvff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrycnvh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgekuxw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2urporrtv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoehtgl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwnlbbs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afcoscdg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2shknqguw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgfysrb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjijljz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtcwtxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxtmgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaalllij.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2atvshhes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnopuxa.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcgblt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzfilix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeczwnl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfpzbtu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvaxfff.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whiyojmg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzobxgt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llkfcnne.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maupdhjh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fklkrrfp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojanhnjo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqetgrm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnixmit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgipdum.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rraggtuc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxsikhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sadlnvtl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbtamub.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2plelywln.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzktkkp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbirufve.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uywonjbh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2usqhvgus.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rujzmdfy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaffopft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrcczrf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yytcholj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkgxpz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2okcvkqta.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egzhtwgo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efzgytib.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imgabslz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcphlso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgypoaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrtckzg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fngjiehn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uirdrcku.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrivlfe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2batirgbf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2davpuidm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqvifll.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djrhwynv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrofsta.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkvrqis.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzibkjh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfoznvf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jetxkeyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cowkdsjd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgfeddm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hrewngfz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldgtuqu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuwmiuo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsuezbi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfwgdmu.html


<!-- 参考信息 -->