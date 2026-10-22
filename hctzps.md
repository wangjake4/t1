代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcltzsxg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhvosc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2einfrbvc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znrilkhq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfrgqbj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgyqelb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnvnuvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfcrfod.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxmctsn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzlaysg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlccxbu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmazorxf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrjxnpa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2osasbslg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2urvqrwmg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdkybxy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqrwdch.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2flifcktt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirsuhlr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzydutus.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrajcka.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxmbjsq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enuppzel.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjepbcw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfilwvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lziytatp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtcozik.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxmpxpq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhtyudo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrxaywo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuldlon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsufqpiy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqhzqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2enzsnvvm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqseegh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2opixfztm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyrbohn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytowuyll.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpftohfd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ulziodsx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbkvwc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocazotzg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkzkjhg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqtbrch.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcmchzc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmkqqcw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2heogzigb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2amjzatnl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2riztpmtt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnfmxwf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmwjxkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjuqpwf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmblmci.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iynzajuc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrlbdew.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjggysw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nubpgefr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmmppv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwbliie.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjgwwv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqaiuuv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njwlcztd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxryitui.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xznsycis.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvheetuj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsastmvy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcucuyyk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjssmcvi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enunjhbv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsbzvkm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmebynyx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtoaubo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2deaoierf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xobluvqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bisvuzyt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsfebat.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fouuhqrc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqhfcoy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vonbpqmk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaolcse.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvhoyp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvjtxpz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewllvmvh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjcqhki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcawrta.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ipexbxjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2repjcsoa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvkomjw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jakpnmsz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yedomzqs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkmvdwa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsldebt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtjijay.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoposhlw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrpdgqd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ducbbsrp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmxqic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfnmmvk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btqaexcy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olrghhay.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuhycng.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daqmmygw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqakithg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaplgvs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otgefsqq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vsapwhip.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnzlntq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qykcqjrk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kixqunyt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhcvzr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2irrfishr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrekokr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjhjjgg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sodxpxbd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrugaoa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcmciiw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmapymik.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwosjqdv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqytjhn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazpfvpy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoqdkeh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgsvimd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ungztbjn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lkemhpie.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuecnxr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvkphdc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqslrrab.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idquxrhf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iciseitx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vqecakoo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqumbqwm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjznitsk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xooypnln.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsirqda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lktxvtwi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yldeqqpd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeebeybz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eynbtbfn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cjymiwqg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqohbcl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oblvabnu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkeqrzc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oathmfhf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2anjfdnie.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbddfy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaigsaw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dccmpykh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2blizmcbo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhwiouu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjpdhvv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uctuemoh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bkftynwo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzpbyti.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsdgiyw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdywjoyz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmolznc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrjhoua.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpbqgzz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxsujhi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hngtrzvk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuvxxgv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzaoclk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2himqunov.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmuwlax.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkomkxr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyalpxsh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqfagnt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatlqaq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2aoevsrxs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmxiebs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vznsihga.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fajyoumg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sriowcvu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rylpwike.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtztraq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2knlcmtgh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2drszvqtk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hatkmhpw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbyqujf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtuomho.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzxurld.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcklxrc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxkhsjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2npbhdxxi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlayppa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdnvafa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edsgpjgk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ennekygw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoehbfn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpizogtx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvrkwns.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbuspnb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyfmkbm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiheaxg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjflwxgz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqypdwci.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoygcny.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtbxkle.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaycocq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pcftalki.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrspkxe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpzaext.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgzqbpa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvfzxle.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxcemjl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2utmdvaep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwdxuau.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnbzoww.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqalkpa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pofxqnvo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cypptkcn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxytlam.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekwfvgp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mtziouim.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhreiez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pviecnbu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2msvwoayb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiflfzko.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvakxswb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikunxkdb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlphyif.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuibuqk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhjjzri.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdjbili.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehehzijv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojtfptz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2efbyyjwr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqecawuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kowybadi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzafkmf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nbccmdgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwycgwj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuvstdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwjdsa.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvxrqeq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aezfriyj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslfkukv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whapdipe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjzotmk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msxfiutq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqopfkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrbhlbr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kstabdbg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kalvusml.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzoktop.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaigolt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtykgzp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzdhefj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgxybzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlijooep.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjivxfma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfucexci.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhcdoc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuggcokm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfszvdv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwdxags.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgilev.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhcpkej.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2joayzbgn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gocgarul.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2exfybxch.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uctasbdx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aokgcphl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhgkrbl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uabyhkcx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkjokyx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nenkbwoq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhborvd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwglflvc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcmgmbd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrszyklc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jaclfwlg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuosks.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imvfrbqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cljkdfvi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzajxghw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2szbiipif.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ndluycha.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdnrowu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcexwga.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnerrla.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwmekoi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfzuqzv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpsuwux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbawruvz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpzpzis.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgmvysv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eehppalp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkledss.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnwgym.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohipfauf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqmpbjo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2olltdojb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfieaixj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzaiitk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbyqpot.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztwkvqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2isckbrat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnmtfgi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qogdzspz.html


<!-- 参考信息 -->