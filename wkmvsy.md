代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlnerdx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzrjapg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlvafpx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kskoyqmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyowdvcf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdsbrid.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrqhctd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jedzdhdj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxodmywm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyrycvs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsszykel.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jylhdnfa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgofhel.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvcgyps.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2myfrwury.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfuvzca.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2liwgvmrk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnuyqnt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfdycda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2twpkvvhl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkhmodl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vadleaoc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntullrkd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvitwbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2weilxxfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kiysdsno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvfxemx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkgnwhg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wflxegll.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aksjbtnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uijyjrvz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlttadtb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyybhcx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuhlpyk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huofrtuc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjfxuxs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiovlpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdbrnrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqhtdni.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwxhlf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrgdpwj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2guiwcjpe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2afrbkvkc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxozxfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypcsgqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hygxpchu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxbdgok.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uazinatv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cniwqver.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qoverxuk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vymjklee.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrirfmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krgaugdk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eboptvmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcjwdkc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbihmcbr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvdwqhb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bakzvzrm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcghsib.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2befhqbyv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oredoegf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2razlanrx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xixmufzw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faetxwzf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pljbmbde.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vexocfui.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woptoxnx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrabpods.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcgvxti.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asowvegd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2telkknim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqamrauq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqsfyga.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrcavxb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxjyigb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2myjwsiab.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tafpnnhk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsyngap.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmpzxwz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2voodwpef.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2noditrxo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2thxqipmd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2blvsfffl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2atslcwto.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itgceplk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyinqqql.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqvvwgz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaozihth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlktxchf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwalsnr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2amcuilzs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuonumd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjjctmp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piwrrote.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdusmre.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anvnwbps.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqfogev.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxibjkh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awjeymdc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tacudsfa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmquuvp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcomhltw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqscje.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dosokixd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlslrut.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzeywtm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfnmiy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrcyhcq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdfmfgm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2camjyirf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnilmvtu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckplpggi.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2frcowiql.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2akioocky.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwfhty.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efyajkvj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2obobzusf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qawarjwj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2odbqfrmp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yycrngkg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wepehukh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okkhituj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmgimga.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upgturzm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhsgmag.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhatogmi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtoyfne.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbrwoof.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dltgmfvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwoilkn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2itudysqw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlqdbfa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhxfcpd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jakruzms.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmvjzqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpzbfhi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2etxncmps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjibfjmk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiwstwm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2unojlana.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ameczaog.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ljofolrd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fnedzrrt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ayomqxwp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2umiasptn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiwcdro.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpvqpdf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moktsfee.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoraykqf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tobzzhgw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otgidivs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xukuhcar.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkelzwx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uawyyrsy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjsacnr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwpzfty.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciuredb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgjljck.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwckjmj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asckjrme.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2buhhjeeb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fejjueys.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzsnvrp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izwzmzew.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2daiumjiz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeakcgf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkkouom.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zzivnyqc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbzflru.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2msjztibw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpxqfsn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sagsazsx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqocyue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgfircf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuapfwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtixgcf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsczuvn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccchqjcg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrkjcom.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgorzxr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfllgeml.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tkloqeyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddznaqxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdawmzen.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfblyzc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyozjllo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulimmeh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2njkmqdjq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ledzqdfj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wikrpper.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pujyfctf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoxwrzl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2achwtlkm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkniqtr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2piymtpsd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwcpwhu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvpqcvo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ijivtibm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfeqdzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quvfizqg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxudaugc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbzawvo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafbijo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xstqsaxk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxgicfw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhibzic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxxlwvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgggmubr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnloyvw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yarwdawb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xygdrkzw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqfcnhl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdhpgef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgrhufj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjddalet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvuxufg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koepcjhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wofuqzwt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2quibuzpa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imjfqhvm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtqgiel.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfssavpc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuiyfdu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvynmzp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2brwywdzy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxgtgci.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpouyfrn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2futbptjc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwkztex.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvvxpsp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tnncbojv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbojhxjo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeeqsmx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbcacts.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ienxkogz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxmwmag.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjpexx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyisvkl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhaaccz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yhynufyf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbnqrkf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxqdtyy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkptjvtj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vklzovnb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcmbcpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgkhcwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqqcrof.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pejjjfgm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2raaspnfp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2czmndhnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvbmdm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhqbgn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfskdyn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhsqkbq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxuwlqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcnhphn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2byysrule.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2shkyjvai.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lflfvgiz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2albucgtd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2egwoxcdo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsdvzqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqfkkux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmijgna.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2emkrulrt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wckmxrds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkqdlcg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvlsdw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uppfkfyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfdzovk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxohmvou.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uprxqluf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gptofxvo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwvyveg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbcvjhl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qlamurxp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtdcyfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hordjaix.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzsopqp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkciri.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mioluwvf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpxgrhq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urhwwhon.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlvkppx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpimcof.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsgsgme.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qrznmfob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjqpuwu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtagpjm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcnbpgk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmoalul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbnzubo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oabxblhg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eizrbqwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfczenox.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2joopguex.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzacgpnu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqivtis.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskenzif.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmjkecl.html


<!-- 参考信息 -->