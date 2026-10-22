代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhogfeda.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebikguqm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pibjfayw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpixysr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwbgqj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urzdpycs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrkprjy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrrbgmy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtqfvyg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hclohqfn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaoljeo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibvpxv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhvxaaq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2irqabeoh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqowmcj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmkyvzb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmogbuj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2trxaquzz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdpwnvb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mpofmgoq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmdmvow.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnzqsqm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrafqko.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqcrxxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoqquwz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwcqtrz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpidthmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gydlbpte.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2djeppirv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfrvmwe.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeurnuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wiooucup.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpcqhhw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2naqauirw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxuzybu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcqmjl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2leyivfxj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvxkfbd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cibulvxn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaesvuyd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znrepgxb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2diojtpbf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xskhwtmg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsitdao.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zprmbiox.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlaaeef.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzecugza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwszhjqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmatkgdg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kssdafoy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2haehitgm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybfzfqn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwojbkf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlujjxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2invmjtvl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2csxqwnav.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxsopfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oysybkgs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxoowop.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2frpztgoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsfxlms.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bldngfmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iebjalzg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2enayslrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgzlmbp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnkfrch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohstxyah.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcchzgh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwhfsvu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czhaecwv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmahqqs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqyzxbd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jypjxjld.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnklumta.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2muvaegah.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfslrxwf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edvtaipu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xwknxkkb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olwklhqg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atftdoyf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmutsmb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbncgt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnmuofp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wraujgrk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwmmehp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rudnrxei.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoxjxrj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2houesafc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpvzeuz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2grtzyyul.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkwileh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwpayb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhllhdk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2afqgniuo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dxctegys.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2brkmswvu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnacrsr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jycudwgw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaxagtw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqhdejp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2quhfxmfs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grditivd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2peejeguo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qplrhaap.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iyviqhlv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teovqcdu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auqqxpis.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lihsdnbg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwvchar.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeevumw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrqumot.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcihnyub.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lurtvkbh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpapqkn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clamlgou.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhqyxtz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqucafx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpxycab.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2goupcmib.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjndwknb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyjamdm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtngiqg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcibmjc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uduqdwru.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aldkhwxe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2byvbfaff.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hufwpaoe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsshbdfi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaognfi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zadalybg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwbjhpe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrdgkes.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxtlnyr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qufkvwro.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qctwgfmp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2albhqyqb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtfctck.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqlscl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmpgjfv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdjard.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuszwsx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flupjgko.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiblbru.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexzglzg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrlzrxq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2linnszuu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foqojosu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqykztaf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ileamony.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbxckvv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2efzerdva.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdqdowd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqragzy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqfjxkt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcopmra.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2prxmnixi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kqylqont.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2asubleoe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrvswdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdubziu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nisrlvju.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhetjwu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drniccxp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifndlqz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzehztu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcogekc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phclahte.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2igumtvqa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrzimig.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prlydkcy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnkbaob.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yffzqlpx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2apijszdq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxarwyuh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcqrzvq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmffqfge.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2isywgemb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2usyjibpc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgvsflh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2syaelbss.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwszhwaf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2trrnjsrm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbefiaf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2shdaatch.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzkltq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqfjjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsyxznr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjsvuhg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsyjjvj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnkersf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipraaft.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxxpdnl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwhkvqh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnbylmp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xucxciym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arvknaxk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2utaybabc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnecsta.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzpbfy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2arhzscbi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfuora.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlixsby.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wumaoqig.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iokwdyjf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfyocpw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdkonjp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfzvvf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcchofzn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyedjqt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2leqbqprt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnmoftj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asubzpjh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ffghbwxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjmxbfl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxyfqwh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhmlqcs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivivpjs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcpcugv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pneguoyh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrwvhub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kmebqijo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnbnvwb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krjeirob.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyqfnce.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uchybuvn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eforegsd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mepwjphm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttebcqsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awjxuxkv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrgaixw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nssmkogf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfqknkl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkknmvt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcdiin.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkwmzdc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2khdjxzhu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckebvtzt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxabxyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2utsiwyus.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvhifsf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyirfonx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akdfoilm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnkyudr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krghiwza.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yickxjsh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrsatqs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjxpjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2azyaswxh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grpmdkrv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmqdkhc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljallolo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkspaal.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtvsxag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dilsrheh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrxmmmv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kflcqfec.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxcoqem.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jtchswss.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uahwaiti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtxrca.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2huigquzc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjnemuu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aefbvyna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwceuiq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwstatok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfnqlkl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2debfcwte.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfwgekr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsidixb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwfsbkb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsgfqnl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tknkqgly.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eonfrfwz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbtezih.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qujbtziy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hdouncxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlaznkh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2knfhxpvg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmmenlu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxisffxw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtgdgef.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfttsbp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoucpsm.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2seasbrir.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhrreqj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aznyjgnv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjevbjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjfhbkn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vejbguhi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjgkmci.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebqetm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afrdakdt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vinbvwqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnllanue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uutucnmy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeztbuq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2aostpjxs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdorvkdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdpqzct.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtvewgw.html


<!-- 参考信息 -->