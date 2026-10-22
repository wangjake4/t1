代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsjovgz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjqhznz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iboindwd.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oimlmssc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjfelkl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixowqmkj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdvobjg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdosoakb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoelxgtr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbttfy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2goucixpu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2btcyvycc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvpdalu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlwbzte.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdofdfso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvrmpv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egkhupks.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlqvxob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2anmykbcr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyslrtd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imcyhquh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzcyvqt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jghrjita.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxrgybc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwqfijj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owkdmyuz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrkzvw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgnxyni.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqdsrue.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfgntok.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkspjoak.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlidhpv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmxlmgz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwravhs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tygayjyh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbauprpi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oftutqeo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsdjlze.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfyjwnh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbqsgjf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsumaosw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdponfbx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeheoliy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvjeke.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbbberz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpskdsn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrxaazr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2niefcvtk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmievgt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvtqntg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbibwpcq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsapjng.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvhrdso.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2epdgzggs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhvdtnj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqkztkv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxdmcws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gaipkqvs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqidxli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbfzxri.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgzbcca.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtmwmyt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoamscx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgtspgc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clnfwisj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhhipqj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iodcxvxz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxoldm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2neajzbvx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyzszmp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqemtjil.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvpxcbc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnfnahx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amwonfkw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhnnyjr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2csckctvx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrnmahn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnjfefj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gctqyzcs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xroxbatf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2omaobuum.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfrxmol.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2farxdqxr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gceoqrfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kphnhcqf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvqkodv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wowtrpcw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvazzibw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxvatnn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzosyoj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngocvjrj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwdprtz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pypqoiqc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbwnqwx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uciiuhzd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjiiiop.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2veyfhror.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfditbe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhrxvvd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzsfbuu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjrfujf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxyipyl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqqvgcm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqeggqx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbjkxcm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2awmxkegk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wesxwaab.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnmacpr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgyigcu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iyndbwed.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pelsxcfa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtispw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlsherm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2abrkdyhr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzypzej.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uluodvki.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lncfqzoo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjybnwqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdqmpzn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwwllqb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqabtokz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvahjiz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawlsfhx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2khebyruv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2smgtisrr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elctvecz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agewzhqz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwovuxoo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iluwceoi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2znkvpgbk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbqcxch.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwmlhcn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zndjlafk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yurbdvmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqomumnr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnbawjt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfmmdih.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimcajc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dntlkcwx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alpesfyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyeomkd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yozqowxr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2twzehugw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2twxaxrjm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqqhqkw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmakvkz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrfokof.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2exgljfvo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmdrceq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kevsjlgt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2upvmpvly.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcnyboi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyfucih.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmmbvjg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvclqbuz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjmobks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtvklwh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvayeqwp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpruefxm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgdlsfx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ustldojq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynvxwbp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jiohauwk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqncbez.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfgzzjl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibutuqti.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2segdgwiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvpzljc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfighhd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxwurmh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvsfqsm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfgaxg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2umhecxns.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpbzzeq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhtvyew.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqrmdlj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jllpjipq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlkwxll.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnzfdty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljeoff.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgajkhg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfxtbez.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjayenrl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgcepfe.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxtcixy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btjjxtxl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeijegn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrqxcen.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgbklde.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhbpbjf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvogqavl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldsfpqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnaatnr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpdqgnx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jehmpehv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxevjmib.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrmqudr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxocaael.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2laqriytw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2acvmwqdy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jrafzpma.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujumca.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tagssxzb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmfkwhc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qtndgcap.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zaelnupj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmyixw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2juqmgfdc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuczlby.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnlbqbm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oytcnpio.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yknmknjz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2epcufjwm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcfwfoi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cuskptxi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfogymtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkqvas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsqtvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgxdim.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbezenx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpkqfgl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakinjmh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fdimleuu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2knnpasig.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkvatfq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2algaokkc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoqthgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2edrfdjln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lncntsgs.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckwrpg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwialmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sezxrdnq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2olyoyvtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpebtgg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pndazfqz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsbwsve.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wljeecbe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2festhjew.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfodzgi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxpdlpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fldjxifi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aclibbbi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlybchon.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvmizni.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2umhvzdok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kerrnitb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmlgokp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pefgguzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2necvzxyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvquddai.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrojmgl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbeqjri.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2esftyiud.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbubksi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2azdlpdav.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2msscpqfs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2emmmesip.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrmkpaj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgilerao.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiwlmyt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbeetxu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlojvtm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmkbmv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgycjlpp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpnzoo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mquhfros.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kahfggka.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjihuewh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlfmwi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzorbum.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvmtzke.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pefpenhp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avsurrjy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jempedaw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdyxoai.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obpjdywf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasmlcxz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdbgpbw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spaleeyx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fyavqpij.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wayrfdwx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhcyqx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqewkmi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wacdldpm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpzkmqt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghneyxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdywhrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dullpafr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsesmgi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2djmmtnwk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqipupt.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwbbjor.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhvbtsv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgfoltb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uywdhfji.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaruvke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsdadhd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmwvuvi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2klpuezem.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxipbjna.html


<!-- 参考信息 -->