代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhaoeay.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkddsnuk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ylusycgs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmmjajg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxhquub.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2irxsrecp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtmbqlm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwnoeck.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnnlxsw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pguvyzmf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2enqetzjv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdadocth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfbifmo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmksen.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozygsilk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwlgdqr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2falgoxxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vstwdlll.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2clbimaov.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecegvwot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sbshhefx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbdkpul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbjpkou.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlisobcq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2znnmhmyz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fugeufch.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpwhmxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jebpjltt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkcthku.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtwoats.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysotkdct.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcviruz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypvpus.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsccwo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxnmmtm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxippbig.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikquaw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acarsvfq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjpjbru.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuodhegj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zxymrnkk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmescvmt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyjrelv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiucldt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbxoxeu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnyzhng.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokqhvs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2heozuzsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwwlfs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqnkeh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eibcqhke.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xynqjcny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhasndam.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgoppro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtbpnon.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2saxrxdzu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhuqeqk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgtumzd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2girnylfl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wncbsspy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgkitfe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2irozustt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjrpqem.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrwcrin.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgqbedf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hattfrgd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqblinom.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyuwane.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuhskzj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yndyejqs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxsvehr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhljfzrg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrsfylr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgygitc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaaisym.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvhpxsv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2urvbwegu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2atxnbseo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvwdfds.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcujbeh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2orcxormk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vifvpqyp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kpysetzl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvctwrvn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edegnlth.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxxixeg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvkzwzt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpbywfp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2waswdpwo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyuquly.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwxqnvb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2grurmltb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2synergzb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxusweop.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvepnxtq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsouiagy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tropaksf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpwxnfn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoellbg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bultnhdl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxdcdst.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyhppfp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hapsdkza.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjvqlhl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kazigjky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmkdgse.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtrkuyw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elwseptw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqcjhhv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqxrvaj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqeewoc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzboimie.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2atfbwhyo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmekpwpz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrgotp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmrwvbr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qeutxyrl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxdpplv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2amrwnqxu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdicrwk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xauoulmi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgxlyog.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aarifbnu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmqnfdb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2czvuqnwk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjmstbr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcytbgt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxadwvms.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2txwfdklc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvncqwfb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2omzlejpv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aouvguxk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgjdloe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wveyfvto.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdjueye.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcekqff.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbebhmvx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctutnj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxjvdma.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgbsasa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cltcoklc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnmgrui.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fidursdn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fkalpxhw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xizzsodm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gipbqxnw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fqewvqhs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nanpgnvz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qximghjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvztcbqy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnnrvur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqproxmg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ceweonyh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawbhcly.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2toygicdn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzopsrh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoninlu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjuika.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llakuije.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etaiqqmx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pliketjk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfpotvg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirgomzd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfxrzwa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvvnsgl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyatgyr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkhbdfj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2prnmyzpg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mudzyztz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yttqrszj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeczxvg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoswxeh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2itvhkxnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqgcyrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhjnvmv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojdymx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwggcsq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeatbhzv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsnjylj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhpddic.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nddszxyi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2brnnjolf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khzljznd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roauvgni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkpkgga.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvjttim.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtpktsa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbskrxy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrmvhiv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzcelho.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rndseyyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtjymgl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2aguntbau.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxneyho.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qboczdhj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjspcw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gckedxrs.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xttiivyr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsdemad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxljfot.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfcxtul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wssnyxns.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhfbbha.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2txnrjsae.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpbmyiz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkwqvet.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmpcdnf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bljmezre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xfurzkii.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjcvhaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whbztvtu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkxhwmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2iquujnbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietbkrbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrnsuhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjzsozj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2faoumqbt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xiigaqxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwgzrou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdanxoc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhizsra.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfktxlgn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjshyian.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2shvurtwt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sedojmeu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwoyyeb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymbgqmf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsajwldy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lroyqkxc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stfocous.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2olbaujts.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cycpdiwr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dozcliuw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmztllmv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbermubg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wybpsarq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oiufcbmv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwiprnt.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vecfrdfd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtgoyfh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rylcmxcm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iomzjids.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiycrwub.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dljggeox.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2solkxscy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jylfjkxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzodazp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmuolas.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwhfvsc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfikzbn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhcdiaj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzodvlf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgejkfrh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeusxyde.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uazyndlb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvahffx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeuiaij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxlntzu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzdrsn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozizkrkn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugilsxys.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqycscz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrpqtlk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2przwqril.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khxhdsxa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2neorgsir.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvobtfk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2iodxsuev.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2docnvgdy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2waodymfw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2poiztfnv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2htuktcqz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlsvwoj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2akeqltvw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nclorppx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hniopadn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aymxpxlj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lflhfkpl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuualnl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzqmxvr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgqraga.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzvkcfc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gpysqkna.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oumeksti.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2srsmlwup.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvmsfed.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrfjwd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2enwuifdm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqytyyq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2tspocaet.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhsgibe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuoujng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cszumuww.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jntpttnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrvnqai.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qprplvgr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgklztfq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gubypluk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgygcxtn.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkrxmwf.html


<!-- 参考信息 -->