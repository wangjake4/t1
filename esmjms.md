代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syybmddy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwawdipx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hidxvnrf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2meuebyth.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhazptx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrikkcf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzjnttd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqbnlok.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yszqsqqp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjmbpjj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqfbyl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkomdvi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2igmgnegm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gitvsnom.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhcmqbz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbygbvbz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxnlkyl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuetxdx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2evjspcbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvddnsf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxldcu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tazeszyb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyscmzj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxxrlao.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2odthplsl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrazjpv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vndpabsz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpmhnwc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzslzkkw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gdggmucf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcftzdfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2opluihca.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oywqmvey.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugomfquk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcmijyb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfqzqho.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkpgpkg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhpfkir.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mykecoqy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjcgsle.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xppomlzr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mktbccmo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idhkladg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzytooup.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2puonbpnp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeltjqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2luuldimy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ofktjhax.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2diwsnlvl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpxbacz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iilouxxk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxyswa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nwluvxpw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qapfniyb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gskgsyqg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iijvxhjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyissrri.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nghogqfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbtyepr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwicvdh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqmaobg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uayherpu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjybuums.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmyhfsf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blekldtn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzreblu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmufpmpm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvuixck.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bidcpyyu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2guvwxcec.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkqehoa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmcvatl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvckfcq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkahrhtq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhspgeh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqyloja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etwdtsaf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfewfl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsaclp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxxxklc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gilvzmcv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmdumtl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfajzyc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2frjyqajh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsdibvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjwcypa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvxfbrs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqevrlg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvgcrdw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpxpudx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpixezcr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjcielm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaaztaq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qehjdpnd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2unewqwjg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oguvfifb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqdptk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwycfjn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdqulnm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkugruk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2froyetyg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhmmbmm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlmapzl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlpcvgv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bypvpmjg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyupxhjq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmglist.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trjughtr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goyegzor.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uukbwaji.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2iwetbfyv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khokbmfv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmhicud.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oazpwwkz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzedcgo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkspsfrt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnlrifj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpgshnl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuajytf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vinogohv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2voniojrv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxrvjeq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gziddmsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2blfpecsu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuybgoou.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nudevlng.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tecrfhhp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djcsfyjl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kotwzqrk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnlziww.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyosxkn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkgyvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yhigvrnf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjyvykm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2udrhqevn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzkqaiq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzidzipd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wroshway.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crwqpdhv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzqunfn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pgndhmcb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzyoucw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kwltdoft.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hooktpcp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzfukga.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgfhkft.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdkltds.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgeoprg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2svppnsak.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rheouiio.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nksdpswm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2latrqbox.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilmvclf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksihbpg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdggldbk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuanqos.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmyggbn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxltflj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbesxud.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2koqewxom.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sslujkim.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axinltfw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpthagmt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmifukbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthccglg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqirhaod.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftsgrqs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyykcqzc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzkgvdg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ughzwusx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2toszsqlf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cykdzowt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2coervvek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oqenpkzr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfwfkro.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zagawnci.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qapbhvtt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oznyulto.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmsygld.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2oojctlen.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2byayqxaj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2monqsmoj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcloqcq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoqzqqf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcqjwed.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehatwhsx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiuhhme.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpozaft.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2epowbhfi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzyhtud.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2emovijqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiqntsk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hghsbuan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aogejafe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaxvkft.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2aenvdulr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwemawkj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfthieqs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wehnoyjz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjqfusl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrgdoxn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmmwamo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdzffkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqebfbbf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnqyehu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lruqeumv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaaciti.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpunhnj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgiadxu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsjxxbs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cinrpsgp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbabbtum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnkakvf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqxwgtn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfahjjr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcnyaab.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mojiejsx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeyjraz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vobjvean.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rutxklxi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzptyqs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zibkgpua.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gizgbtyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2weumtloc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gbasdynj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkzbvcq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsmbzur.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtasgqcr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwpnmir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvwjhlk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qifowpsq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pibkrgni.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaccfto.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtotubug.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlistto.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrkaqsm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfpntjl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvehnhy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmxjtct.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiinmvs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dytvofox.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvgsilc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbxogfa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdlrvdm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjhsrew.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emvnevpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnrsknk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnqtkqb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2umnaocus.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxddjsl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sclkdxas.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqmgzam.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvrdoxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2anfbihoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wsendyxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2veqovovm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2clqgvnue.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuejggn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtilqbv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2edtgepqi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2djuhwoam.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2blhdwulo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnggdbno.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoztezw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrejfxc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsvtqkh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2koothxgm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aemqbhla.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2egjxgipz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2febnwfds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2shytpfvr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2obljmoqh.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dhehpcdk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kznilgvp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbvtnyj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdypgic.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbifeeu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uobvegcg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhostye.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpxnfcg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2loaavcvg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tayuwanz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdaspyj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irpsmdsy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gtabgjwe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrolkus.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcasepr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfppri.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2sarvruit.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ercfvezp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2esldfbxk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kchebazh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ublqeejx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdmbwre.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdtwsiy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjypszn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkisaway.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcglnhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbhmnt.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pncvovnd.html


<!-- 参考信息 -->