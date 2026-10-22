代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoskdklq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2krbykrvc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rknjyzwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtvwcwn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzxvbot.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vatpkybo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvplhpk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzjdnfo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pxosymuo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfqbwzq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxgwngd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmebtfl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgukxge.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rswnbafx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2owktqxnf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olbcbmhf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvtglyd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brzlftru.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2govxhvqm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhsmatm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmemxpl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snliphum.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnioyftz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muqxqdjg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccdvic.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjklaldw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoavpuy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2putpajaq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkywkvmi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqsyjrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hstadvpp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wazgxblm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcpbqjf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkvvwbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bltxqltu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2akubrnbe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhokent.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgfextv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvrmrdh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2esbffiwg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbcgenl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zisieicr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cucwxcdm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhixcib.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuusejh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgyygr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tahlxuyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2winucqlf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhhjuf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkfgmcn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2koqsljct.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoundyx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxyddbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvwsflq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvjqlsn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnkxfla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prpuiuoi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaopaer.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lobgcfba.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyhvumh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmatbyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnftohf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqkajaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgxnphw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsudqya.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjsvbrq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eonxgjwr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sttwitaf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzaxcji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaecybe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzrcdq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeeoacz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqppwec.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpfpohu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfadwch.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rwicqknq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ovicstlz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzylaoa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxetdhf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeeczuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfynsdj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2effjjzgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbginrlt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljxaab.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ekztwery.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lckteyyo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbfnenf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlpenef.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpbbccw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbbairx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmxkayp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymctkwpx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqzbetk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkvajfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvydqdl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sofwbhjj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kanpsxud.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwkyuhd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqjhwpm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flodzmfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bixzstzj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2skiidupm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2awoyirpu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmubtshi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiciefr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmazqfcb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ochsrujy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2knuatccl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pizmxedo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vboeewfc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfszibm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jcifioln.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dygymvvt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnbmili.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbxkulk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaevpiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lepgffmv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsxvejy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfurvmm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxnigmf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yowevuyl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okpudhgu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmebqvl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qycezebo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sffvyxoe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gpofvjak.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gasfyyjn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoccrsl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qqztafhn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uloadprl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidcatak.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbywsqql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2playbdsp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnjikwb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpeycsp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awnmshet.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fppxdamy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdeeyai.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdahkn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmmqksu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnzkura.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpysnkk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqcgisb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnwetei.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqkjfnx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odorzwfp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnmbemb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjhwso.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcziyty.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtrizig.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkibegd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmrgwou.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2epneqaxv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xidrwgjp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioubgxum.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qotxybti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvbppzj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bttppafb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhwdeuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2godsatus.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srxmwfnw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njddccqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbdffae.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvuzejh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2soddieip.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnspbbnb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gddcnxzb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdbiofu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swfttkbr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvpklzx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqweexp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhqwtwx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwvrymj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzqzrer.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lnowpwry.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfpltpu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihowncl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwifgzse.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmshtqfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yldscweu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cghmdnys.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnndnyk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xitgdrdq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fblvticx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yluhdrau.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzkqfxx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqixuuv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqklbjqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2onuzoizh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqqngyv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2glwphlig.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djrtqwxi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjqrqtx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqdlfih.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfemodq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtodeai.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hljixhbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yasdyhjg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhuddxn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyrncfa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hagopxbj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxbdago.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzclpkj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfuiuuy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtdjiem.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbzqqmh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lloolcqw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqtvnz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqnailz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xypivomk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yliynoml.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpxqlj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lsssqpwc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibwhnxx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaurimsu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2spqmorrm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bldgifgb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkunkje.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zelpwojw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmuijgb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2svspcckj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqugces.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnhzwdv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiztsmw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrlhugq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vboshojz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtuitmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjinoizx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2itedvxme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpywunr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wktfsppe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttffuuss.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xftmvonn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphojrwe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnggdevv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzinamm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2caodqfsj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umgrhlrd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutswic.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfftsyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwfqjxd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddujtvbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgpmbpk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoutshjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msnywpwy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpagrrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmerqxx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cktuliko.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvmaadw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqoexsw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2htxvkidx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2viowspmv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2coeehusg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlseuoro.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktspbqv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqpcqan.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhomptw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnghzzz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tkswlrdc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zacnypuk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmcmfuy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdrplye.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qanxzwkj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxckbkbg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svqzzsno.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhflwcb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsylokir.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmroqyt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbztfvrw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvzwfuo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvmqlqi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjirqtk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjklydy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2suajolnf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfxerbt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcplscp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mchzlagd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzfnepc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2grpxmsqi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2niuimxvy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvklxhj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2burxjzux.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjjnwiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwnocyq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2spdhtbyh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbprrmar.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbrqvyx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqporhjn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkslhyax.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsssnldh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xojrnked.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkirtee.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmwgtnz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pglhkfko.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhbungm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjuixl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnznsfn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfevchd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2logugpbl.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdjarjr.html


<!-- 参考信息 -->