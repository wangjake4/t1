代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfftyg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2skoldhvy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ohifdkcj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2byunhola.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjomdsgu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjwqmap.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmbzknm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2alqxeywx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xisxnmea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmwrqub.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuhqemm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kktwfkpj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2archwaju.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfeanrn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpknpnbp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zljxijjj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkjlngl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiklamq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2herbgxkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjtbfxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoboekq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwuqbww.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2prghplet.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riqgiufk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwhsapo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2chxgabkq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjhhavo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvarhrxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgcspcm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzoaoho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrrjpsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tagavyys.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaaqazs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmofxmvq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unllgxxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpfjtur.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzdjbrz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2saniahuf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drushnaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlnvxwc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gspocxwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzgmbjw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtanpmk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrqeehy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftphifv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2czasqkah.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2awjgtsgd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvcxflo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccyslr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vooxnmyb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2epcoyseb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiiptsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkzylfh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmzczic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaehnhgi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvddeyx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2itstsydz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dulzkcad.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmgnntz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnobsx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbmmmak.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2swwwcsaw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scnffbzz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmapytb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bklseveq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmwysbx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmvriyg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scwlqbxj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjisqhf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlajnrnm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokxklaa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtxnlpf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcqixlp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ilngynsl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdqwhvd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2necythbd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2orstxmkk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qeveltwi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrbuhvo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnbsxk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehitsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwgkgpg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvxgtwr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vdquyrcc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgwsygz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvweuwof.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lisfpcmt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkkkhzy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyxaekb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcfijvd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zybvmpif.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2onyzrziy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlcixxi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bytljgwl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvmtvkg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crhbobes.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoblkks.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jvztbqar.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtlzagf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mexlokek.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvhqyuw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rswqktht.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpyjuna.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfidqpu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msmtxhgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baxvhxxo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcvhpu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqzsyzr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkqekol.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsplxsdb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yasfcouc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2emrubzca.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnphqlk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxdhlkq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhwqakv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcdbwnj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pcojipqf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmsoofx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtjpmpc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2aigvaqid.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvqclsd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbofleh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juneicuj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvoitoc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2trpdaiqx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmwrirs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odrjgexx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zbltavre.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgtkhmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scfbbjit.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiwbalg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyymhgn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wampolhe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmrggt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkogqmpu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyxkkwn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwbjanz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zahoawgm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaexqvs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuojtwg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcewzsv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rptlpdok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrzafqu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lklmugkn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2chlrlcxk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkzxpk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gjirnmwx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngqlowx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhljsfhm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwttbypc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlipbox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mciprgyw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cibowshx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2degrmbue.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhkjzlw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2riynkmlj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxbwhbx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itxdytbg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oubfecmn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjbwqyf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2leooqriv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxacxiqy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2elvadiot.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omxhjuev.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfvzunn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuphbye.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2afzyqtws.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2csgxqyhl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnlmqzo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjcufri.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2srnjfuoy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nrekreuu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tmalszhb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oewmjbyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tqurcwve.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bglexxqr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyzcmto.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxiozyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhnvpoe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsndirg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxlyyyt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qujigkoj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbymopw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqtwey.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxxcrpk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjfhylh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoimgutq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2byqacfci.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jysgytje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnewdjy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2socwupku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvprrmn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtujjen.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mygdymcd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxqdxi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzuwunz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqembe.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2grfrklxb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2huijfwrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anqyhhqo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xschkcqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epcfemfh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnjpqgc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqseudcx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajumqknk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaxksga.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnrgqrj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgfwcop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gceazsaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaioiauj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpsnbz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2huwsdncp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xztomuaw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpieszyz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdaqseq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auyrhruv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ichtuwcc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mceasaxy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjotxlo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjghbzki.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mejcfxjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmkfzal.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2efknvsej.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxngvis.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdsotlr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xepdgxot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcakrwga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjmktip.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpjsdpg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnaauyn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxiylat.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipobxntw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inxgsjky.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdskesh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmtppkk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnjchlz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbddyiji.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oswysaym.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onejjpef.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eurpgrfj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlommok.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjvopfz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lakiaclp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wipukwrg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nucovife.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hollnyhp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeuritu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkspynx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlxskkd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aotzdrxp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pdslibas.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdomowe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfpawyw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydefwqwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbssgtj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmndfwi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvdgyjt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwflakzu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slikpvme.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkuzalb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbaoxug.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwqagr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiwrcqi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmwyavb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmswta.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmjibgo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjdafbm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2avicmuwg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhxmuul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqfwfiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tglgwymx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2aorhfzlt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsodlzz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xvynyuas.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqfefxn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hebnfoae.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qupgmljr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2omikvoys.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gghkkjex.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2netjqwcu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eragdcof.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxqicct.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tclxpqyz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2suqhpqbf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnapasm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2aehqzpmg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxlpmi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2avqlmxdz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlaecue.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2edllopar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gysfebod.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igwsdxqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wptswveq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqjsoof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2benctiik.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jblxrgqw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywxqcek.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxxwzki.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drmavbsa.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbrgoig.html


<!-- 参考信息 -->