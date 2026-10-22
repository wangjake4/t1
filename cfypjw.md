代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoktbug.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpytilk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtgdyhj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwgsmax.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuvrtge.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxigyjwx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbpmirt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbucgsl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwzgrei.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tniglzmp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzufuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2proyspak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeanzxa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nytnzrnq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqrhia.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxppzspn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcngsqvy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wobzmnyb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sncrzify.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzelngpn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2maeeufrk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvstvyls.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvzvdbo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ityfzdbb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lvapyodu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecckyctt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtfdwmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2furdkjmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdygckw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhqwxiz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkrhlwr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjowurum.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnlsyxs.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsfnuea.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hludaoly.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yetakaxc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huqoojgd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvsjmyv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hainvbaz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnitjtbb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbwbwgf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyhezvh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjlvwtg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmkmybr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkeewfn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2epogetyl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfrjuzn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfbhloi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyojocnc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwaxuqd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmixteun.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eixjkqyb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2thibbhgp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpqqyeu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxjmuls.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvvkwai.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2prqtziny.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmpopzi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aguivtbh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbvenpn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjfqkda.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjfxuh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iacfjmzy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xyejxmhi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtitlhw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdtpcdf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtebujd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txwrhnjf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2njiozsri.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfodcquw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elbwmmqs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftglipfb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msaqfvkc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpifonhp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2snijbach.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adudivga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzufhltg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usdmstwz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idzlbjpu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iadoevck.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ieahhbeg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhulmmw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imzyafjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nowluzpe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcfowtj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awbfeyvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfeotqr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgqueuy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtaajjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2koymsuyz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nylwjwps.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2djlpdgmc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtpwgxq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nstpjzxu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvejlmn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ijesczrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwbfvvd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lohgjbfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsawcjx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fepiygqx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mihshnob.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2totywnbu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkazxqsk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpwncvl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evgmwsws.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvvasem.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezdovu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfjaohp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjmuoi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xayidhmj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifxcag.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbopbier.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inoksznk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmtpsqx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgdxmps.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhyfbif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfksthw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgasbuo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2slocdevv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfettkuc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxtywxz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onzyupch.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkochcsi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcmvql.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aybyrgel.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpannpt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdjblzr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzqfnmg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdmtxoz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpraivz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njvejaxn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtchlyr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcqxlry.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrhernv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjqcmpo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2llhtijub.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vmifulth.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbmbati.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eayubiqz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgliwr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmipfdqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbraud.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfcenwc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iokhchvh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gyicikgn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dikmmeru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqfwjv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsrterd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxenwbd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwwypsh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2glevxrww.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkyoaor.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqtudb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wehitmev.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtglooz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjcxqqc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvwxiba.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nggptkht.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqehzcv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cphfhkbp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2agbgbuic.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbcfoop.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyefqjk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtwxgmt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjczvjkd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhqwfps.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kesiydul.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwhiain.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpacusno.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmetuia.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odqwpweu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhdzqqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgknpsp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmompdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2arhaymfv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccqxugu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlqjqvu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiofclyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfirhoef.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsxcwyo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2delahfvc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqguwdgp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwnaepw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oigexbdv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrsdyzi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxgyocn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zobhqcpw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nevqivxr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2psrrddyv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbhwfmg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzrymky.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erddasav.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhwytju.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsxdyak.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcjisle.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkqzryb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvkcan.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdnisny.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvriholf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nixkggfm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apbkelbo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldbtlfe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kegyzbcz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkydogdc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivllyjj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuapndl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlqmmny.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaoztlb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuornmnt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnkbkax.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsuchab.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfyzcno.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dupbdnno.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xmryqwaq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkidxj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2egixtxln.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpqsmvf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyenaej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnxomfr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqqljav.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhqucaa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpnnkci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsjckps.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdqbtkt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtgqcc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpaznrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2siddmcha.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvpxccq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjsmeah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqlabtg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqviridb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrifncnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhxcrbm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqyrnfh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2naqkeoie.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2olamgjyi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtnruue.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2alalwqvl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2klztsluu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvclxej.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fkirsehf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tatasgmo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2psjircwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvczne.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdwnog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhqaiod.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pfscpxbz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpuwtzm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzcylnz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbixexeo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdcrohd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iatmtfzy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmpttvy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmmjjmn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrsigoe.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uiadtowr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjqzsuh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqibjdqv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpexvcp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhcxlxl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlmosyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nptbnynb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxkbqwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adfxhdto.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jekppdnr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlybalb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqurmvo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyqspnm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oypnclxc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhadqetf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhexkmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmpgvak.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcdqpyk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vweuipvc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmjrsoj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbkomta.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbmadlw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmfpxho.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavrzmc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuebmyg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njczygpg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpfqclc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhcdzqa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lelpfqnx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwxkuvf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkrdds.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwaxalu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umvcdgag.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2feglcnvw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdkddyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzyypqu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmcayaz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmswecv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkoqbna.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2paavwqeb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rymwzoxa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawgqwbf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujocgtd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgaybri.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfflkmg.html


<!-- 参考信息 -->