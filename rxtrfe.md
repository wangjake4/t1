代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2uplvusia.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoslgpz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjzipjh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2opddazau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvmfxfl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkclcvl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxsjkny.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqmrpj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwcbhvc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqykvf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmkarsw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bibhxjji.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kztonzee.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkcwkcv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwhbxin.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgefbcjs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2eynmegok.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2svlzmrep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2chdrxyik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2deddmopv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iprgyoed.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoatvzp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupyzva.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spizrdfs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grqrplvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldupxmca.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2raefxqbz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urockwuj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrvjzuy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awastmxj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbusknab.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mionbpbh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyfcceg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2warhmknd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2smbreljs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtxaewt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtoipb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfydnzzv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2orhmnlun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdfbrvk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiqjgej.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rppyagxu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfsgmts.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndfebq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlnthth.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2snwzoerc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxeprrj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdfcauq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcbwcvd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkkcdin.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xispwjzt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2unhzegqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wphaznpa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrmyhtt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuxwpij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfaiame.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bdswishe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpowirgp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2niczcfvv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmfqfz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2werouacq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvslopx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhocppl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itdnkcbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqvpjvv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dezpisgl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dojglblr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfposbhp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbmvwkw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqiywhy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2opfeqvxb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dodedteh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwqbafq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whryywtd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwqnlan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqrcrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooavykif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bptunvbg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnygwny.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaimkoq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jmefvgil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kifpihez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbeqxii.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ylinfyvm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2huuzzdnb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lckqqygj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrtmsxy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vahfcsqx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvkgsrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhrffmo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyamkvoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2szssgrmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcifstl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2btbcqbyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyhvep.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kpveqtls.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mnothuoj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhqrwfd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maceknpb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anmdscif.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suonoinq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvswbdpv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djrojlzl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgbmdyi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avskwbrj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjuosjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laxqzjli.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuspfko.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yntbkpbm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmjffh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vubszeon.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rollntqi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bujcmrvc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wimkelqg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bppdimqj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2svecesaq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wiacdvkg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkugrny.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vswldjqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqmddhp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxqlejc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ageswvzf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2frmsmtnq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhdldzw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lphdfwpj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptexqedh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjozncj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frbzsbjg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrjuzsn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuwamuf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqgezfj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yafakyex.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kocamtch.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfdnqr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2domsoinj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkasuyhw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjirgbmv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zjicxgbb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjeophy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkcczxh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhyhzgv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpgdqnh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etktkqke.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktubdbm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdywrorg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmggzqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fadlbpea.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrklgpb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxerwwb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvimcoi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhrmvoj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajncfmlp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smxbmyad.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2httogyvi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xflxebdu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqveapo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnlekly.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rinqacyv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2txffaqqd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2avvybkvb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grgarvei.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nynmxkwp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eemawvys.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpzmrpi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbvigfz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2risfaojl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxtmdqk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gplquhdy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrqgncz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetlbabf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zxszjzlm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nssqztvy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fziknvcs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2attfwthm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhelhe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghkcbog.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzjjest.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnpysvm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kskvemwr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2looijmjk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzfhhmj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxbzicx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwllayv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzszreis.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xbamglod.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhsadym.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyqnyrm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abnhighi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwxxfz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsfaupb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neewcclg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfllupk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2acdjgwyy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fksqwpdr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tutcdtpf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cjixlsdm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqtvcfi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xguvnekw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jruixkys.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgmmbmz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtlvfqq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2crcqayzd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swsizjwb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqtwvpl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuseqin.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhlodyd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2muaokvnt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehozayjb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wcngdqsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwgszgb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgazjjv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iggjsfdm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfjalqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kypkxtjs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2puhlbbcs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2csgcnyif.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeojtutr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhqbipb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwqyjmv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaeuyis.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xefobzae.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szvxjnmu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvuzoeu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqfknye.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmpheu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdzkbja.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sszlycic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiprsyln.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zaztjjfr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsftmdt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2auiolisx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2khoudyjh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2amfcidpw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywkjqfk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhfzonn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ingheotb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fuludokv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtixdme.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2paqysglv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mebeurgt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2esyvzjuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsqjfst.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2odgykttu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2phsltwlc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapffwep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrcbnfp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshmzhqt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsvtlbh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyuubcs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nthrznbg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiilspn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsvnqri.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dykcnrms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iovdusnr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzqeqwp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyoujyf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkndlvxg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdzbeht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mexygphp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgayaew.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxumftc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzkwrui.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mepmxtdw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2shrorboa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvhetdm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aavyubyy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlxlwmy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkvtcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2neivcqrc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qejcejgi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvbfafi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vragnudj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plbbcmmd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qixjssri.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfymagy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbchbumg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eurwwiaq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zczlepdn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2thmzrquo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtflxux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2podylfve.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mufvqhrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdnasal.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxlgdka.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlosvnh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyvtxpi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saralqon.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaftncz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdlpdb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yruebeyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcnpnwu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgcdcpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzzdpx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarbndx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwfjhfz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiifggm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xkckxjxi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlngoklu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbclkju.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2saitwadm.html


<!-- 参考信息 -->