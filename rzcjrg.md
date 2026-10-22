代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxksmxdy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijscph.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rivepvcg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hivqxwlw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2suqfyogr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfptabhm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iptqhtux.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zktiijjq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zatdsphq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zloibvto.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2enmekzwe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxpmgqe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqddndyz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2okuwadoc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2davdxlwp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vczlbnir.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdplcjr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjxjan.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2phbiyghy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgrodpe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvhakrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqktafx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rktkhadm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiiqfno.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvhcwci.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2potywuwq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpstmtc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzfjiuk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gclgljwn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlaqung.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcxlcvd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reispdpf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izuqwrlj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqnugfh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjnjwbs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlcvfex.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfumrvj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2swtxpgyv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxjjdki.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbcudvi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rclbaqjb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjwzbls.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoppste.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgjfjfx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwfrgwt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxtwxew.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsojykw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjqbsjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtrmltx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqejeev.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvrrjkv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvtlbfk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiwfopo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ninvgnkc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2askyymdy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzfmpcj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqgddhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdokdle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvuoayi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glkdmolw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqemjzt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2knhoxexb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmolozo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxioytdn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqxecpj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkguqvtl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvcftpv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cijpdcfj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiigzkn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwbwaik.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otsvlmbd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwdwpv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cribvpbi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmhpdqz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmntxvhm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhznptac.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xobiqcyx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsbfjhg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhszile.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yphklzgn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycofvmj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjzwhpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbuhaz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuiqaun.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kptghwoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2egycnvyw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqisjqsn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmdizac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdbfaa.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xnngzhui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzwnpbp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbqsbgq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbnosap.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uknuiimf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpocbigm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnaplot.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaxedyg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdpnpzg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzlmmbk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hniitwaq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcliglhc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2trtjngab.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmieol.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwbmjpk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yogbdtzx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyieais.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhnjvmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fpniixcd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pryziusg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2knjrryho.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwymbnq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicjhni.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbbxjlo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhyiibi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bemjhqro.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vheevdef.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2goxtzmmr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyaymly.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsitvci.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iikrwxde.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuoapzd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmqxhzc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kncycqdh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwuhlhy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aneptnio.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlporsy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lveewqpn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dodcktkr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlrloco.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfirjte.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzenfsad.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeszbcdx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ughymrch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpymdbr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xijzhyyf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqdixst.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgsnaal.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2frgzoahk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zokoxrwk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2habgozue.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvsgwpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbrqhm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjyosou.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzxwwmw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwklhfq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rnixhoqi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2saeizklh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzfzopu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdnmld.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeupcsj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwadgev.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2psvdjght.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvralav.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvfbkpo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrtbslp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cphibrlv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kicytxbh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsadwphu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rouccwxt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsvurjo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2skuoygag.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcrvwpj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnwrzwe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoxckha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlxmvlp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhjpykn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsasski.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdfyvsa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujwbbiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osiyduhg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lulqibkk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlzyimi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbigemd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmjtvoi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsiryfy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkdsamj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qliplhsa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgeqyor.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hbarokxb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsuasod.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgapqol.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bjliuvsr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoncsri.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knxkoocb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfagafze.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2finimxhr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavfffus.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkchrri.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbdmuv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzibvfgs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxssudju.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2megrqvsf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrstexke.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pddforkk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igsmyhug.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozoialp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgaqxvu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbofykw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrqyuou.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbpovdy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvefgen.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzayeyk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrsbflw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvglkuu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsrqkfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxikuev.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hawzvryd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2smzasvey.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iynoksjp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxnlpiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2urubpttz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnqshni.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2usqysrqy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpszhjl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqfucmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaoobxe.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfkqtbr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwlpbjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfesluk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqzybxq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaknxnq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgobqewn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckywydas.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aumfbllj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gaodhfkp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mummrunq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2krruyfzb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lemmluap.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjpnlca.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmbqfs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlgvarq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjthtm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaopqdi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhgzyrp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2umgvwsbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owylfhwm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwlkwxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfqhtpb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqujxoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2clptuyhe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duebzjqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gclgcukn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrsrudx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbgktxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oroptgxc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhvvova.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zobpcccj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgyfaze.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmffrrq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eljcgfws.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvkrcdb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyuygjc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brniehlr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdbdbqn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbabwbt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmycqbu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xplqticn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pscpwvxl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcnnlth.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjqahdv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsbsjn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdvxkbh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglujaw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkwyoiv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jssizrqi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbncajom.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yblpixga.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urwowwqx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbhulf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qspkrkfi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxujmwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2iusswrgp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxufoujb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgycouc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpumghiy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuzhniq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgovhzil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyufnpsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktflnbhp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icjwpwgd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpmukyf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2irarhgdv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qujkhzrx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cdruvutb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgrkkai.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgrxkoy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wlopzrkq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hynpccgh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuekzvc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbtxpdo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdmhcqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ttocxxjy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jtisvmpb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hytabhyd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azvbxudt.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrycbub.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbzosen.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2umqfbgxi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnwkwgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ggblwmnf.html


<!-- 参考信息 -->