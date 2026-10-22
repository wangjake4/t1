代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcceyere.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhmkreb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdalrqx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmszzux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqfuoxc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2auzkzdzv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuppgxwt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2piyjjakq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2odbihbin.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxhzcev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejpxpoc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2faaqgthk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2evymmdsw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2aazlxnxi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2thgksxfx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaleuypl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbwiqpr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awkerppx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmidhlqy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wabamgrn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfenpds.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqwzfvz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kboruone.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpetprlo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2winvptkv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idbhlsiw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qowmxxuv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvcfrkh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcopcyhq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmhuioz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dowhnhpr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaeprxk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsyxbcl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkjhqiu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfooult.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yigyyclk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjdugxr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuuruzp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2okvhvnzu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zckjgexv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkajxat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoazsah.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuclygch.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcipjgie.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2arzpfwer.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhgibg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2krvwmdkb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgswdlzh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uksyqokq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtovwawv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcdlsx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jfisgggc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2knxbtmmh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdullgyx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrakrft.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfksks.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmypjrze.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyjnhed.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqnkpii.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grouxtvi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iffretvh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtrpql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhurmgn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkedzut.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dumynoab.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdoizpk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnemobn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snuwkpbi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbthpexn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbgevng.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxyftql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixytkoh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lluccwbf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlkojou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynwxav.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ectjagcl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvjvqpb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibyiwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cylpnjrg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafrbew.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xafipqgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxucwal.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtjwvkj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfhdomg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbkxcd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqngvve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyojjned.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yehgeptg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2inwxawth.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxelzbz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvctctvf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twkrqrju.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajizlkgk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbthpld.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rndjflgx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gayxoguo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2navzkggr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jspxjkib.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thcswaju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zimqidoy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwcqvdb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vupnfznq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtphuhk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uawvzagr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmljzpc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qnboiggl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2axkrqbpf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfajdcm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uknndzcq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqhazpr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2raebbhxc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gwciencz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbhytjt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlyobtx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhgpqpm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmllnxre.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qquwlbks.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hesxmfuc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxwevzm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziztdifn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkazmdw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeypefm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgiwftn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2orthyugs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mgifqseo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrnhcxu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aadukaii.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksodphiq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhgdwmp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mqalzlmd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdedoduz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nexqzgpu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kkorhbjn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mryjxyrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vetfjljl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqksvrxu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tivqeynq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvrfffb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eieojhta.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoolbee.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2urmjoahc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nzweijzy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mflmzzyf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwctitv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvgpduz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvwufls.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuajatw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xraspciu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2urgwxzui.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbvbbfx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxtglfi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhwpeas.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfrqrg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skqnprem.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvcogcq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofprijkr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxugfoup.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyqasri.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgbaaev.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2togmoetr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjjexyf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtgagl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgaxgok.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnialrfe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrttisp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jijtldyd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbosdkr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkpqaen.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdiamlm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2liiydybn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eczgfxtw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiazsey.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2haohidfk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xibmqmyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwlcoa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzykcor.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2svnqfoct.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mmktkygv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzctykc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlrojgm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vknzrdtu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsinufgw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdxylmr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qazbjhqk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iunambyf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuprywb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyzstml.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qodmadmk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgldszv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwfduot.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprkdgrb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnxkmdf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbefhtt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zreevhmv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eynqndbc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjnyoy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyludjx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2djbpbagm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnynzzm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tyczotwl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlgptmw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2evlnqoic.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrpsnpg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrxvsof.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyobrsf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbhcdae.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zplytlgi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcujjbvx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysziymrq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dscxhvdv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xczazswf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazpcal.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2apddawiw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiuqicr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2phmkcevs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqpkzqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rufvvnlc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjldbmtu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtuxwcm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlynhypc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ustnktsi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2frihpcyy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzwrnaj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nmehhxfm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpitdnt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2axukhuow.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2phveenwx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qikmwxvm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdxuuhd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tclypand.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lyirstju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaicqlc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiywwpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swqiytol.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedkjoa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkidibo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2inomopml.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdtgdiy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcopmqec.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsohoyw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaalrbt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyprjmd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbleotj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2toaefyae.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrpkwia.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebraebwb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tddpattr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvrzrvl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnavmvr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxeyhty.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2prrfwaae.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfynzhz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmpjtlw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoqdzyp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2egxmftlg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hieaqmuf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqgxewu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbkbzlr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rysfyorn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqwqykp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2spjaerye.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezypkcjb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cavuwzot.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hckrchne.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxnhjhx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lliyzxqr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkdzqzm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2goaobozu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uywptaeo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyjrliv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rartfcuh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2apxbhhkm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdnrvdo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxocqad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxdfdg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhzleaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbrrotp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2npyulnap.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nacuwouy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwwgoyb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lswnvamf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzemlspx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2clbyxrai.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oagratwn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rglnbske.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvgajqd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpahfin.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevqtat.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uykyitbj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfufepu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzxxnwk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkujmqhn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2labtijbb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvlpczy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ogawtwhx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aeonlypc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtlltce.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ayckixae.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsjiudt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfotyoxu.html


<!-- 参考信息 -->