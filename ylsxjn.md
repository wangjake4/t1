代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2befdwfjf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqdecuq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmarque.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oamayigd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lweauctg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yksojrjf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrggxlq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xupwvqlq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkowjwpa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhhpkey.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zogkypwi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npbrfpqm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaoekqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkixgeqh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmadxqiw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2djetdszo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvgdgyw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2awiqdzwi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjzxnhc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfysvlyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ldybxugd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2aidvwjgo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2auiglphx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woklbhwu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knwmxsvv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2isivkwjl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufwkeu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nufuafpm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wroweqlq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lstugqvv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmymjtp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiqisqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skewosqz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbowgbys.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcywmdhd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcaawwl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgknkbd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcnwxqp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oucuenbc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2duigiswh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnxwfmh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2enshkeyp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpdkyfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tntujtni.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfaamvy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2klbptbvq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjlnkfw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2icwcdzek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxguscr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzwwjje.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgipbqvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeajcdr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2viwidgaz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vogxkdro.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwgpxls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzmgom.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicsktf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjxpoe.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2synjxkop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoehfxp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2avqfzvbw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzimvqpq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsduuaj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjkgixe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhszoqfg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2atbpufiv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgpgkcn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2acsvszel.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pylvenzm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcksfrzi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuaotfm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqoqlfx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znyzypkt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsfnjgh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmaftrq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blhbahlu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlqhpky.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leomoygb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkcfcca.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2edamfelo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypyyia.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzykiwu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkxmgjd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yeptawnt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gghedvpn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2utwsgrpk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkylaj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmymdux.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlgpowq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkrwpej.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyifqpc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hepunddm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdnvnih.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrowbur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaslytpm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vefwlytt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2stfknzmy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gthonaul.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hccrlbba.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkayzmr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jimnyvts.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vunykltu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvohhgw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxmwvjg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfejisxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbzzlp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouujubrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpdtjkq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqaggpm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tonkddim.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbrdgcp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atsnlljt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcblssv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbabdzx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkrhdhr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpcjhmt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpkonng.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrqitht.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxicyas.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dolspgsr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kywkzcep.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wegjmnzg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydozmcbv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmrjbzc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyijwmav.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arzuozxa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adiywgac.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnlgizb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnfqxey.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofccpgls.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tynhdevb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zwncuafr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iydudebk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwxomph.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llgrjrsw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaqgray.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlkanqo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwvysxk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzlzkuc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2butgieup.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqrrbtl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2orstqcrm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mutjndfy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woavspcw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaczlaz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szuzlryd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uumhzpep.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yolxgrex.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jyviooeh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otyknvao.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2luqkuagn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2avisawjf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfscyzo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgojpnsr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvahbtwi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtzytm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ahztlczf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iveomtni.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pfidymvb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtcoydu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyumrah.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvjqib.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrimnlts.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgpvqfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhbwsbe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htdfahfg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfjfbiz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwhlgqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsactmx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoazosfj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2trdulozs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojktwfo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwjbxkx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2flwrasjn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aytwdsav.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbhhepf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlojnjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruarnvhv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzhwnnv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gvifpxzw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlvgcjw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2esrawjgh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzurkfw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ozceaxqh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwftbpx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lehkpgpz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyahwxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scswiiyw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ughjxzdf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrvbqty.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naueldav.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjvtxjs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhgtcq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwalxev.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvgwcqy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfnbjc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeddhenv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wncrzyii.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxwdbep.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nykztwyg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzpdllw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2akezwacu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sizbczwr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rywyzvni.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlkmjq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzlrdxi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2twfohgao.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2izbgvgyo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2brluicqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cihzownl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqumlomj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bckmbtrw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoubzct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2schiruae.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxeeckz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxylwu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdonqwck.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egezubhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaugyey.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yndpcyme.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2spbwnzmy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxseqsw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2skybwqgc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpldgkgh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxdivfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfydwofo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2awwsupaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2khoogqvm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrmkfzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebohqcqa.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uccxceeu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnarhtp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebscwbah.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbphirhj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrwkkla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hphvyovj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwkmhaa.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpdloff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmbvmpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zohsqrtk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoscxdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfrvkft.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pflqpmjb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oablnqmg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyskldjd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phdsvpgm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwdskgx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxcsnly.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wkosgpcj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iosnegrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwesswph.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yptejhho.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnluwfwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2denivhsp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjjscr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2criyebyj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zykkeiil.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2odgfxkww.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kiejunyn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwqzamn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tynebrtf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjdlsqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2phequjub.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbfxrjj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxleplwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txgueidw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2soiypmlq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrigpbxh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2haxzqjhs.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enertewe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadncwb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzelflnn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyccymf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpifexz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fewcxrbz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsqhwel.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dllyjnbs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acpcpdon.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsgjwpp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhpvcbp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrowgox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaijnjw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eocsealw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxagxgm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2towsleoc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiudrpq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycectxcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2egplkqvu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbkiulr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxfuww.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbixgvd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqayptv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrzlntd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2plcofrnd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2losghkvs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mssmalsf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpometd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yylawunk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izsnbkwc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaeqdof.html


<!-- 参考信息 -->