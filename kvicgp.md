代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyccwmim.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2crpxefnu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuglhtp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2womsnxaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrpdarb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2augykzih.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtupatxf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzkxbwj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhylnwkh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvsraer.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpmzoj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dljxzvue.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhukvaek.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlvlbpm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pahfxgmq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxyoazh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwndlyli.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2biqhojuf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vikxrzpo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqytgok.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwrxhm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afwkdcbc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtzlshw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2osltceeq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2brpxclqt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdivzty.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2imzqrjal.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnhfpok.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cebvfyjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2upmqfvnq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bikuweru.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uixitspi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeveulm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyukjhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtmqdse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpezkcjh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfswerbs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reewfmtx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elaifkrt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujedvzbh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdfnnjb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqucglm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmspbhk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klsmphen.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vljaujtl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlysumg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmgjggm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbahprq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkkmuhk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyldxuq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2luyxjiyl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxwthch.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2adglvkfx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2baglrflw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzrzmcd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zufsbuuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2liynxrmr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2irldpsco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znzaaslg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvpcba.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhxaguy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbtgjfx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njqueqez.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsposrvt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luqvzrkn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrumtxng.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisfiai.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcffwdod.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmscud.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbnzyzu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnzjlbn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsbbgms.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whrelwhp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koegxjuf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aimmbtkc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhncjubh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcybqkl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zakwmmbq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzmnhn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eancdmas.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoykobl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcaweym.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jecjspsm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2evsabdbb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2orsdmzza.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyojywr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbqjkf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvjugfw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtohfkz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbwebkg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncidzugn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oavelcmf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzdlbim.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxujkaw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hubwltcp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmrhgji.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dwflmuiq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pehikswz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjcfrgg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlwagw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwlthuk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoxipoc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyabpipv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnroehwx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfeqvwm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcizjfn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwuexdq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsgdmaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicrkzof.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmskdhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjhiker.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhvibwq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hrthjklc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dveaprvw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkdocl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2faadgznx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqogpro.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwfeuxx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqgibc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uknboasm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjuzvuz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2culdewkh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xowbczlb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfxfonv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdyeqki.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlhqyhe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2higzviqr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsnsxoy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dckorzbn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2opadapfb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuxrcbq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfedobh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuxjobn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjhowgm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tczdkjod.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrglqsrc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccwmoeu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktrzop.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhpoqac.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezchgrac.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwrraqy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyxwvps.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxkalxk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2glzyzgtq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kfflrvpz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyhiwnm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqmdckx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlbdjoe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfumypv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kufterxn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcadcmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dybfjxql.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeilmdz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqdofwg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycczklsu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqovdpm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfayvfg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdqcsn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhctgge.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdttwxb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umpbtmzi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awqshois.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlmoakk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyxcrum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxejnek.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjaywft.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuhevfk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urdgqhyx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbnsrr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaymexw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbvqjpm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmdfgxo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnrsvpv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2entfudps.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeoobmy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jhldsqqm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pupghjwt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2znjwbjim.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhryak.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlguuf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2myoznjhx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmixdixy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccywduhl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxssbt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsodkfcr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpktrhb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2extoehme.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhyjkia.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qazgfqfo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoybzmt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfnpbga.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxtamsc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwnbcl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sohjbtlj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfclgkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwwfxt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2krznpada.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwnphdn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqtvtgz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcwkblu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlxewuj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrrxaoz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpgwmhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nanasmcn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2squjrswj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwimawz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2phhieoto.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvzyqyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcblzsj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exwdokol.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxinng.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeownzvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uixbnwjn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjcvkhh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwynfch.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wytvswkh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqqvmmu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrsawdf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjzhmpf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcziewx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myijzldl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvxzjw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrigrkxs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnkijiu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2daxxrwts.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wycdkfmq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsridfoj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdbidzn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwuwott.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2djmewiyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2djxnurzm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2adlpqswu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eynbeail.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgnxgcr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrafrqr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmipxrf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyiqzjk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmognki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxmboc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynespjdz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjsfcoi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abswffuw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndisepbn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2supdqefb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnxuxz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izpsajcg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcnunsy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtzmozu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhkvozm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ioevskqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuavllw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqaokud.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ntawfvvi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjddgln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpflmtj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiweaqv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnsbdma.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmewhhme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sglhjymy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbpxpcv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2itxrtxno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcafqbp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdnppgc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pddrgnkx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khedhgbx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2srgmjxrj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhftixp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvodwed.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjapqtko.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ctysdpre.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2usdqnhtc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtfzggk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjonjlt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzaajzg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqfaag.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gstzrpps.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlkmwtw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqkpgko.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwvmocl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhhcxct.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2irngdxrq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvvwisc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbnljvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvybdumb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2arxzkhyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihompuq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbxdwsr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmnnicg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwgxsnp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2clkjvafl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxcjnwb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ewelkrkw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmczdtk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dboleiup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2epccectm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuqxnzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxccjxpi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqpanqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuozjus.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2icdneudq.html


<!-- 参考信息 -->