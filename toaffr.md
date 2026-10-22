代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2llfpjwcd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgzoycp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrgkhfa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzeksfa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkoaevt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnomzky.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetkvdq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqalbe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2blggivfk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljhsgsg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2usjkfuwd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2emorszxt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhixqwpc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbrviyf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2syijyzps.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nekxjwfl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ixitgyct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boagvzws.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrmgmrm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljzmfy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdyjzpd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeuftkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2pybmmcrm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqajyqav.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cfetpmks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2phoiuevj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxqfmhg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrwvopm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hswliapm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbsegxl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqakicot.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpnwcnc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdbfoyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqonrcw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nomptode.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvxrvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldajskrg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuiaxrk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpymwizb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojymkywx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xoosyifv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gseokwdt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokvsep.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeafafv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2exixqlqp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ldchidwr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2snouunki.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcchdfl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqngfcz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sehpomen.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxvkue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2heqvxlgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbupjdni.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qterghdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fonsefod.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkojfjr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgrbqja.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqqfcld.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkpjnom.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lewyjrvp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enybsbld.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojazgkem.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpllayr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezffuasp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjvdyim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcafkzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmninxy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cycscibd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liwaqgii.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osymhlxc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooomqtdg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rathuvuv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocayrusp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gealsawt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciscxktg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uepqhwcc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikigdtrr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fiajajta.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvzqrh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiqgngl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2twwkpacs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtddrszr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdddzkz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nikoabib.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpujpkep.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhuryxa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojhhgjo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjhmmck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wytiswmy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdispot.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnvwyft.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwpeneg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqoifvi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojapondf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiaultl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srmfxufo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrmnizg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuqmbdt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npezgujq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvigvqmk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zescbsfe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnesqxtb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enrfhtdh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acutxheo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsatpwti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cawzuclg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvtiipt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbmegwi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2syklnele.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvfhsyx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2edgmfrzj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2obrrvfpj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybobksiv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uibgxorl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmhwxht.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lefihtrg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuuvlsg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2szezwayj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shmeyrif.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtahlgc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkwlkoz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmrwdgw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzbsirp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lugyyrgc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzllifwg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfodnbbc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwenxxw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2emianmwk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yjawqjkg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrcmhqk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvghqhj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqysfgka.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlzbjpg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vysdmgnr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvnbggt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itmthesz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkijmzc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvkirml.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbahwye.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rwibtlti.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qungzgeq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwulsme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sukkggpq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfbzbmb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2soamuqxl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2abzfmvwg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2szksgtyp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2risbyfdk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcnarpj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2splzvfeo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzdhwyg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvghxxh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2splhpyms.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wziymopw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhobhqv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlhqhxr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdiwypn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrukcihy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyryze.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmygvnfx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmcqblx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlddkefc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyteyha.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbsiwpd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzhrtmr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wecifbox.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2otbtcton.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mscjpcav.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrznmer.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaftnxl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyziqlz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mzivsfbi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yftaagtr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlwqyqq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyybcjd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyaprzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeqnoqw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnjwlbg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcqjmqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2szhcsqkg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjyeebq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxicglp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsjdjcq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqopieq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vytivpim.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyukhbju.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqocdtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2btrwptbt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hktjtayh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzpudws.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfavvuhj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2asnwpafp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyppqhvs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyibcrx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwogjjqx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iipqdyqw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynygap.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmwzqno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbwhtuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwujoahl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxwvpqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yumhpgih.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2aderafos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2brsuwrzb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsumwbvq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykitbqsj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eibetpxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlolwfl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnwdwow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2myakkmtb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqnpkbr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhjwfwh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfswsljj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfwfeny.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imohqfcs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjakneg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmpqmbl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmijagri.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlprmwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohepcjty.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqrywrv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2sivkljlh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsnsepp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkkzlv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pspccsjp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqrnpzh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfkzngr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkqollw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxfrelj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjzxryk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfmtaga.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqinouc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkflciqy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kowozbwc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulamfszy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqootx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qowcgewk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keyxomqp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehciwbcj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwager.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qycumlno.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwpxcll.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htcuxkwa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saitgmco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwfcpzv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xupqgxop.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcpbvox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zemvomnn.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqtajt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmwbtlf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2koxomrto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2inlhiqcw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmsimyh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fynmqhuc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmweuqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnxrvql.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzzcgrs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpwuvoe.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzftillf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjlvnsc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgtyvxa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkjpnii.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoayxie.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2evdrwxgq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cphuwcqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aszmhyxr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkfucmf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmwudbb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2khrvogxx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2urztalji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylhjgub.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbyfgka.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvxalqg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bymfpyst.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmbgxiy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzendiv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtayaun.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdmkxep.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctypzvij.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2damttwsz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfcdpfa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrmwfko.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mapvhqeh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oxswhpgq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mygqajkq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqogizui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgbwnqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwlebre.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jjinwlqf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cltjaiht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrggoace.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vybqcspj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opfvhlcw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtmpipn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2invphjoa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnirfod.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdudmhv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nitqpvfr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellxmduj.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxvvwdf.html


<!-- 参考信息 -->