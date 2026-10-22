代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2necxrhyi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2srzlsimg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2itcvbwcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhbvcf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynduesec.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdvonrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpzdihz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsvndyx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkliezd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewccdafq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjjomgz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhelxtg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbiskuh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2figumbku.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqrghgh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pccouaqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetgkgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnsatmt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebepztdf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fognkguh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uawoomqj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iejcxpcr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqaxhat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsmshbe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnptnsk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcigvkvr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2icedermr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhazibg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbxaoph.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rbchmifs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gctlydaz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tunqxdji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psrfthzu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwomloel.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaojupr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqxzkeb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbanytr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhcvpyd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoadcmur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvhyeqf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zirrjkpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdibwvk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvekmwes.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yevielrv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrzctqs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxezlgvz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnypmlnx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyqubrs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysnlrrg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzxocdl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqpplmx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzmgqaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aylmtlfc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wadzbwya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2giwhozqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuyeiws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhmfevx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ikutcnmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rntjgytg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzuemrb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkdqmil.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvlgdxi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnciyot.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrogbxs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfrhkat.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwsjnml.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqlftsi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzlujv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pguhszkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhljaupk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdubupgi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmfalyr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csnjejvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iexmzjua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwzhjad.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zygssltl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtcxvet.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtfaxlp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtvcfkq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiiabjp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oomcvblo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwetwxm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuatqrc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfyqtub.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgjqdgd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtyuvbq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdmrvru.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2grycpeao.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzqzpfk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuoqexo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlfiisf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwemkpu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bozcfbnn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyffcvnm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeahvgyc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yinpsyna.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqjetjs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxogxkko.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfsngal.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtwgpqq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeexfycb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdgfduy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blroqzqg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvagnjbw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxiumkw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmgzijm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsbuafo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyipdrw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpialvyh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzemsoa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjpramc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtavqweb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgsnoga.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2opxstblq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvgjwg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqihxxl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbyrrag.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlyjotc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuovaaz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvfenqy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxkhlbm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mihxlaji.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvacxz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzibdss.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skjinxji.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgghtjd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmcmpkf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2widezqsc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvrqmox.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slkpqfen.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpaidkj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvuvztk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqvmfph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjydodvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnsomh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgwbvdk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kodfvyad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcfjyfe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfcjwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgzltoz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvgthg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zosowtmn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amvdbsal.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cmohdgcy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvebxbax.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrfamn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwlbbp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwmytoy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsgyxyu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlzdnla.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbcwsom.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmngiur.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpoerts.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlsypli.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yodolssr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyslvlis.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zakrgclo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvezxrar.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kffjgkrm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rplkszhw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vilhbeip.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgxmmis.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eruqyguv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwdwcej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhdsgms.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxlfuzs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtnxddo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fefsmqhg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsszgjx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoquglt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwpqagg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2swtsrkpy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qojwsjgb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvtirtu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2olgocggx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2owpjebal.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfnlwhc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2smbankpj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkjdmns.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvcfvgs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2odlgsqaa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvlvxna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dazixilb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2sscqlgjx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcrpacl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmwmgpc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzantsue.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfmfqlk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfpuelz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrfskul.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkklwru.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbnlrie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mhktvook.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtnhwva.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdbyacp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2drnsuffq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kviiwzrh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qavodlzf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwkyfez.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzvvhuu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tnopxhbz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zecndiwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nskdohhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aztymvub.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2azkloueh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsletklu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabmxjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucypyamx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkglitgs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtonrgqb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgoyijo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehglpghq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yexbworo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2klurquge.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xltfdize.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuhjmig.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdsrygf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzwwjui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfhdcdt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaalmjy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxozjsbv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgwvpcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuractv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmbbmke.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zztxwqmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2oegbegpj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxfxqyt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyknzvmz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhfubei.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwogdaw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2emhstfzw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2eratktnh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfngcz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wajeypmm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qujrroxh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxejtuf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpbhvqm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiizhly.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbwptc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpvnrsq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkijrqcl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvmavqh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrstbvvc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mokijnjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glzxezww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzngqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgiuvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeogqrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qksopxjw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjmhua.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wadtsdvx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsmacpm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgaataa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2roxmkwxv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzuodpz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ampmjhlx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkdtpix.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbgqmed.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozvuyr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizvnit.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyprlah.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsecjxb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlguobvq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpopogiy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtrfclh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxeixg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpnvrwc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsxcvca.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdetiico.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvcgfcj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2arsuzbyl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmzacbb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2elggmtso.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vektblvb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvdfzmy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlbsjsx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvtfbpl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrzfovc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vqumxskg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2liohtcvj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bskvdqyf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwptdzuh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbzfluq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczxrnx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwdbcdd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tojtetvf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbzfeg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oprorpoe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcxzoix.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpacrctr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnockvi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnawvri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rksdbuhu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mowlvqwq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejhuicu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djfjwrpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbbkmtj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xzenovce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cymcqvtt.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chjjjnuc.html


<!-- 参考信息 -->