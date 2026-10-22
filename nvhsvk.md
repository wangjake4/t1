代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbahlfuw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxwxch.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhpaodp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqgfnax.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2igftajiw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2swamxvif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgxybld.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydievwtn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkgqtbj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwqqnp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuexnvwu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2knqwbxcg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sapsxzke.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnkrsmc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyonxmy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2incrymyb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvrswox.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hatmntnw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzldhgk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2palncdng.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfsjuvd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaohcmh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2juctobsn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qascslba.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hoepelpv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlekjmjf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2czlofvjx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaoecnr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmlxkqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtcrgzd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reidbcqa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzwjnii.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxpcnjw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcqvwvt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mregkgfp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnuzhhi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khejuqsb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnvyksu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omsyvlqv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swbehmaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnsxonn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpbuype.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knlmwzyo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hittzwud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaidjri.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvhapws.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuammfxb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuanxie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzzqryb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmlhoyh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yuezstfc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qeebuktn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kattvymd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbsszda.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lppetrvu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kipqwfqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yigqtqfi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmyrplb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rireiqbq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqviehh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tngfbikp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwftdyxj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onvtnluf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqexybmz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvrvrc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkadqao.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhtphlq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqeulti.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utqfhggr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2onielaxs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enccofjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochgkgnr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqsqfir.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdkdvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfcndov.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmangyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwbesun.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yojyxhpa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnpxrbe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oirpfkxs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pchktcql.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumnprw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvxsmxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaiwjek.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzesxjnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxogglbz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lafpbnvw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnszbqrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbfwysx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbbcjae.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspbvdlc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pygdzubm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2shzzffnd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmionjg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2moekswci.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2drcvfgxs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbheigr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwzlnb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urzemafn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkigect.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qponjwhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjznkym.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twbxaqyn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxfuapj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpgeivl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfyejen.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbzgnp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dveukquo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoldqlj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tplnwqrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoacqqh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyvemiw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjszecz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2plbgldoy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfzjdvw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdubixm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvhfgdg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvdkvwp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oemcjorx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqtjdqx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wiubksyh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzjvmwx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aitgopte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqvplsm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kroiyprm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jinjhnno.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuubeay.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rksfrdiu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nojjhwxz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mystvxnf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qolfeiay.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjriizv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dfayxedd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtarows.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjjhudc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niirttoj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoiovja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ernyavur.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ueewpctg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtqtjdy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfqhlip.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzgwgcj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2drjpzxtd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoikksc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwcwrtd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nffcqbty.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2subjrukt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vzncouri.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvqdbpt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gevrpckt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdjixhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmzdcax.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkglcow.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmtpucl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhitrsf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjbyjky.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzlugay.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspyttrl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bilmyhzt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2utinnhlu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hycetshf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqfuqqe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazkmvlx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrwaepy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyabwxl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhllqvc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nffycjav.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjuzzqh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwnbvqi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnvhkhu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnpqgkv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lehqwafv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfvsemn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vukbkpbd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdfiilm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2uczuzztx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gkobyypn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhttatpe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2caesltfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2riptfubp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkebqew.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzispxo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydfxszw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2buailarj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhihaiq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xqktsrcz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcelczn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkurpggh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bhchuyyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2devbhtzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeipsck.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2spigrjir.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpiknhq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agmjzdkd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jwurmxpb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpbmbfw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkhvtnl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjhqztw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwegomb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2odusdhnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bargoiew.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2eibwrzst.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrkqgvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhycnox.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjcsaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pttvkljo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2blkqjnrm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeawwoy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzobadfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huspxlpc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crazqiyw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2docegmhy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhzjykv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yljuxwcj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbbgqg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvlvfhb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uenigjhh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjffhlwk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2famsbpnf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqwmctt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdozrhn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwzmfmg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wltivvky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzholrj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmrslt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdrswuy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjgityy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfuures.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjdnnop.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouejqctu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiqarwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaubrzm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxuywta.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xruszdyn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hbduiwdi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opudsdqk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxbskhh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npokudwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxytrlnj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcbighn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkttceie.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosnmgc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsylpwli.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuoeoet.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdedxvb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkbvmxx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peplvzfl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clrrppyv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvecgbcq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcsuaqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkemdfap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hgthnfnv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvwofbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgrlxeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hsinduyq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xryvkgea.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxutyssh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpscpcos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eybwnuwx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2abqwlhsd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtndxnr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sktsrcbc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ammuolms.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nubwmpsh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgcjwxa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgkavc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2brbczpho.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcxsslv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvqsqma.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfndawm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2oczliuyu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2esxggzel.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mpskubrp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmmtwwc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgtkoxn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fezirash.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uuurpmpg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yndbqpzo.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2unzibslw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2owyneiwj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpsmvpr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2glevmnwl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2enzoddvz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgruvqth.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qlchzrdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngasddcc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqartlh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxrexpf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzkdmca.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2imhmlaoi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarwucm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2concafxc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2achnsser.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuefzne.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsuhpwn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdkboxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foqzchet.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sexnmhhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmafkvkj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2botmmpus.html


<!-- 参考信息 -->