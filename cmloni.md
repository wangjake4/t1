代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdqyaul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2chdnyzqr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eghhxztk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjulwwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtynzrt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2stdtnzvt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvydomj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uamobrwp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhlhgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbmxkzu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2siwhceas.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjanoxv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpwsni.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyidxui.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwnjryr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzchfgn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyqtgta.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrytihv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqhjdqq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsdkjpt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjtqahb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nznqtxug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zchuayhw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqrkape.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrnpann.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpqdaic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tirxcqoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnntjfhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faixargf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jktopxbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcibpeej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuiewhv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjjuzov.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaxgmcr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjxirxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrcqokf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2btunombr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfkctgj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvhfgup.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kanawyuq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzidkqe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mokakege.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqflswij.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kithrgig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbffauo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hmivwrzr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rywwclyu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2czcllbti.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjwhrdz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrncxkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfuixw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2unmhlnaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uviwvxjs.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgfrthi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nikjoapy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmixwvdp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhniwzr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lulnlpre.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnfjbgv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwstmog.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgxkegw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnwpsnt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yafgailu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiheexl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bomymigk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yyizetgh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnbvucp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqujswy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvxdkhu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obiajkal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aslsbvux.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxqalmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebmoyyy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2plgctzyr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfawaee.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eraobetb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwxgsrc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2krtmspch.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhxwrr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzotltt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2taooxxlz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqkfscl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmvkqbg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnkfthn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbfstan.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swbgcfsl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyfajks.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbfejsb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2chntdknv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtdzxyd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zergzmpw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2evcvfjzk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pisuzsal.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlxyyhn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvileflw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkphdfsr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anwdlmfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkjnnda.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnnqgic.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diliejan.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvztzox.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaafylb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqlemsh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlobbmsp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwznftwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2engbuxqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcvhnpa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gumpcfzo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hanlcsfy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xigcrblk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lodmsbhm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2onvjkwxs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2znummebr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lftyewwq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tptviwkh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tduuxazm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2whctimii.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpbzrzz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuvwhxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvtmkbv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hatibufl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2firojzrc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbbvdhu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zobmuxwq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2okrvupcm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2raddgylp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpsyapy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjqivo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvywwwn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yveemupq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vihfodry.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuotndv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrvdvls.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqflhtpp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrrvsyi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzisakp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sonrsabq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xryysurb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2okbnojir.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbmftqh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvlidjd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yojsbjwo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rlavszgz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyljxce.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqjkmzj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kmshswre.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sodbezff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scgbxzyr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvvddox.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orkyjqed.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpswkfp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwexjtub.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsjgtab.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcwkpqn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phrvqpjk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzmcuba.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpikcju.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzexpvk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnwixpv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bycgofzo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aichjljc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyczeaxp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkixvfqy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxdpxfi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbilssgv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wmogqwha.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zssmtcbd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdqbted.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ulocmxze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kkodgnxk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bntfavxi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnnmhea.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcspajm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkldhaw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gclxvqwj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpubvbi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ganrjjpj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odjdrbai.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nojcyvgr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjqofvd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwvdobi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2omsqxqgo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tlexbvbt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqwrzqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjxhmqg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsfzgop.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkakteg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvywofc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2giabjzzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtphsbc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2itftufse.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxvmrjg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzbjvr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtbwut.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvwxfnz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjjwyyx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yafglycs.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmmaxhx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsxvmxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeeoktt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zhujdhux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsaeayr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2emprlzvr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckvhvyf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aimekyph.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnrblg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naiqdsya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhzpgyz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnunso.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2haaiwisn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdqpyan.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lppaodol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2crrnlbbi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxeozq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzfbdlp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgccmss.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzamaxpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwhbzfi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjemij.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzftdqdf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zasjeovb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdrkdgl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqenkxil.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlcvgvv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jawhfpvq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbsvcji.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlwvasq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbueltf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tohnwesi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rudqggpv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvjtqfe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlofliou.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnnrhzy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpdkhia.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvyrnoj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbgnouv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoxdtxn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuysywr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsrqzoa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkjiioc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfecbjw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llwtdhbt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoozbil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjylnqaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqcawdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zimjzpah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxapygfr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjeajl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cclnsvam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbenyrj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjtglt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oeunqqoy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkcsqeu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szwyffjy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kncwiyjr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2spzpkdsy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrekdsu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdwnvxy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2blmossrh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rynquiwv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oddnsbss.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvknid.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eaehmsji.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbqipou.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkntsrrb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnhwkw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhspzxu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwghvzx.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqgrtzn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2keubqoyf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuarsjva.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bplqqjgc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cyumsqby.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2omkcocme.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gihefvvi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zioheocb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfkvkzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbwszot.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifrxzlj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqssavvc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2olehytxe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nityhztp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2btwelioc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2epvhammr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mevasxbv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyssrdx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2javgmytv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qixmzmlc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgljjlu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmjotwh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzchzss.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdqhpiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdcaljt.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2habodmln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnpblrq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhibdczh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzwibx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgqnjpv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaenjyi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwxhqml.html


<!-- 参考信息 -->