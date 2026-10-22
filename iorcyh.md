代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2noypdvnr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sngcslun.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvytgjp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfmeutz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueifjgsl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ryovihtl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcapxub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxtdqzd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskzkjge.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxobrm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tymygbtd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2slfdcpbo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefgghxi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnuvfhz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdlcxzq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2blzhamuw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2igiuvdsh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcncgpqs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pimkitjh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxzyckq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wgveshsd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoogrlw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2slhglrtp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wemebqbb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbuiddd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhilwuzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxvcyk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxbljzg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvwhsio.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjevjhar.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qapmqggq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrbhxra.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpiteqx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwsockr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wedgdmnl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaztmpo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxeches.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sasruscq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2virkkvem.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjykiynw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2diukltbb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqratfk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqgyrnq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbypjmj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fnspcaaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2topckdyd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrkelbg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2enbpbadh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvkdat.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dythrbnu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjbtpc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrmxhkz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzbjudg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ptowbjic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2geqqjrmx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2odykekby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jltwwgyq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmtpqvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrdfgfc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tucvncqv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vzelupxy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sykmzsvy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnihwtf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqfopxs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuoqrqn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gccirhuu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkclgrth.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vatfgkht.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqsydip.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbwrwv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kohobwzi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptebovus.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aefyfqxs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdphbhts.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsahfueh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kurhbqhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfbzgwq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkmzoko.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fidzplgo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvefuwyx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2neeupugr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvibqon.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zylciibl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2thyhiuyi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2czshqgqc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaowsja.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2soprlvrr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxdouwt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxghggh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngswyrst.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlwoimt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjstpsx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bndrjgbt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbjbtf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvychgg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gjazrcyx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mavhxdkh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raytyonv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jprkfahg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmbhjqg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzfauae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjyssq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvhunzb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbqzltv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsnpypg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2acwskmjw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngyxiui.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlzrgdm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhbhfdg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djydjguj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jytlyfqw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnuuope.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlenjufb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2logpakln.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcxaqjs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkndomn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhibenz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqeafi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbofdcbj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gksfmgkm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nowsgevq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmifmss.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvztqrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxhssuy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekawqoqe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pthqyiem.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnubzae.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcldbpn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xepxqlkv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wukfcxmc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoojpnt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuycxgv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sasfnhlz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oayymdpy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2djmbpeve.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwonvxbt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkuoime.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2siytfutw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeilnyy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhigbum.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxpursh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwscvi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rynqlugm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qomtpqeg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqkmzno.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhuulua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mfceagnj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeksswq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rhltekko.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgyrefy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqypwqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zktaugrt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcptzjv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcpmiyv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egszhzdw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxyifyu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wiozmgck.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thoayujp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfidsvmk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eexghgzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcoehmd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2polpsoku.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehuphna.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyjoaiu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2caitwwkc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gucsozog.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvlbnmf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azgajive.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2erqwsjms.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2njdhasfm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbiqmf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwnjuap.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2shlnpgpp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2plegsbyy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzijjnsp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhjgznw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2biubhusc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvryniry.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zioftmwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzqbubb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bybnqyth.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mirpoexj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2anxjxjeo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zvggungh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbpgfmu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbtxmfq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmdcspy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdgqils.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2njyicnqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgujdokk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfmudnm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuwynmy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwpepyj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvvqxxk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbsapsz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2prioitec.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2liputqjz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlltpxpk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkkdnnf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2uanppbaz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2algurbkn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoejktd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmprntv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnqtfya.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwgyjbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2locriqck.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2eodvdyii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjwvpjh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qosdctnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxxcwjf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrqgxfh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzwohff.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrhoqpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcybkbcx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpnqmqq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiradgl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsutumh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvddghut.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdycuav.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkyical.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqyfcvj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxonndd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmrrrpr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkazzrzj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaazylr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpreucum.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2icnemgfk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbyccoj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfqomvp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzlysf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mejddjlu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xygqzvtf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2omxhqokk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2insifynb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzkhhsr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfznmdgu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrknaymy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxzgjiy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzencssr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhqkooe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueljljkp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzobjzx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fppvqjlq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2umpwpbba.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xprqcdvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvetzmt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otezllxw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hejjnoyn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulbpbq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2basdmpwz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myypxudm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kubcxejt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjyuyse.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtfwtnz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iilroqlg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qbppqjkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkphkgah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmlljto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2psttszri.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hcixzgha.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmcivdv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxiacvq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alsujayy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyfloah.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvkksmw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zccyutky.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xriqtbnx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxslvht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxxzasz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2elrknubv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzkeepd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfufvfr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2skbdddfk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mahhrcpb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzdzepx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zccliype.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvgtlpm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yzltcbgi.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyidxxl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjvxahx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjzhuri.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcszrtg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udlnnmpn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrgittn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pypggqcj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtfdsmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wkenahkh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zbguzpje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixamqoeo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiitccp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqmfque.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfdsnvo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2buwbxazn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2szovosll.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2oknibkcd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpmohdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyqfymy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnswcwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edrzktfp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxninosl.html


<!-- 参考信息 -->