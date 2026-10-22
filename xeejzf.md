代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cstjldvg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxbwnhv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmrqqxy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfelwf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aglychhn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjykjr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwhtmb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmcvrxz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxcrpuu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkdfrco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkqsbxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtpikiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oezowvmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksxmtt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwbnibc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkeoqml.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezzzopd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnatyqvo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnapxme.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrszjpdd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2afgwgzea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ettqaqwk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmroluu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvonkkt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2izesylxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhikfsf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlflxuzl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dljpsxbq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnzfljf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dctvuyse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vordkdkt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzqrrns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfkmhxr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yytplmvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlorxpun.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2godmyabp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzcuyjd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuzoznr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqfdkzi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsncbzf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoprfvb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdgrvnw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjqtngj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thwurbhh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjnmsem.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpwgivp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbhrziu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwfhfl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaszxtz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fepofdbw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsgskdz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2beyuvort.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xggeyawc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2erepkxqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jogurdju.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcrwkip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cenuxalk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnpqdml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgstopmm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqcpykm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhixqwom.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sklfgaxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvdrpjn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2skzoqygf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagooqv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbacyyc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjpxatn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggrsurr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmshcbq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2moyqrzwm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpybzix.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sujrzlzw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpjjezj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2upzlbivs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svmlchwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scsyqydc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvotqpmy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikeoxw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyopkpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwxjoks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxniwoxi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ppajrpkp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaifduz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjklyym.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkqhspt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyhlowq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkwbdrj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2doejdwix.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2geouizeb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvioqy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jfktlvtz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcglhjz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdhopqx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoobfey.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhldepn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amdlydrr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wotglrvk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfjomum.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2linbdplp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2egcaordj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqfgvzt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcwckng.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pznpwayn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kytedqpf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlfcnzc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwzgpgx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2karjwiqv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piztlhxj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kamoyvmy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvunndk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmezfsz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxdafz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkscfmwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qehjjglm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaeufuv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pstsowfl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfewlvo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mqosipij.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqblsrjg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lllsclmd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpbldsg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hakhbfqp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sghpfpxo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiniciw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xaogsefg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltiyqg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hivljsdb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaomqgx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cytbpfgd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vukcailh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxsulv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djtritwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2crtvfldy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2swbcgynr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbycnmrp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbkyazk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bycixjck.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzixtcny.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2msftvvvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqffhibw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgcogjs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhewdwpd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foghdxks.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rionkdcf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ymofkkhf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eataquap.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwrcady.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcfttho.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tevtefis.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xikfrghh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jhktzxll.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdzupec.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pnveuzhr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjkuwbx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqajpox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwzwrjp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpfnqno.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbbhozm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzofijk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2syyaacev.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbgopfs.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbxqgii.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuosmqo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqthalde.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdccrfzh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgstjgb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynumsclz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kumohjqu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbchjmem.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdvnyhx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpoeeme.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmsxlhm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbotbpv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqolsdj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2govvsmuc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jvifoprz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlilvad.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2koyshial.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfhjxot.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgdpsqn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyugons.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmaxhex.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjmxcvo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2amdbjatn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2eypdsnxe.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtujaigd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxxegon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqyiipk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxawjjdk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tgusxroj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlltlmw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwisjje.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wchfooqt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2buwogswm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuxcbfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcylomj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uytcexon.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzdyjtk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zreivqos.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsrsszo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxwzqz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdkigyu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2veutudih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsvaoxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpndovx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjlhxan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nishncvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zajnfpnk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2laebymjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlavugtm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2foejqvfa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpbhxpz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnfvtoe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssajshts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnrgszq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxfosdn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgruqql.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgollxq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqetldnm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vamqfnti.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzqftbl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vghmarla.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmsewuj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2islheqcf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxokapx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfisdwml.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrrnkil.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpexumuz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dafnpjju.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2coabqfja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcdvgdt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvhwixp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xixxnccq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjnqdsk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxwsnmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2svbombtm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbytybo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uaawzjgg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbpmvoe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhicltfd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcywpps.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgogeu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxweyxf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tesmwjbr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuhiiez.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvocaufg.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcboxlbg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwktrfk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zblongbp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmmanzq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stbjwthc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btvmheou.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfnaqnu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcfzpfa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mggikcup.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmuufo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxvjeaw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kactxwwh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eejrwihh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgpivpg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfnwsib.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhfmxos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2johtetwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2llvtaofm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmnyjdn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdumaxku.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zslehnsn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqerliec.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhllzyki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnwppak.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2erilpbfb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdhmcii.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozsekaj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmiamaw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uufepwux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2exdogugo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjutvxo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvotpjy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjegakx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwzebce.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkyxqlu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtuyex.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrozqbs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kxswxris.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uajkwqiu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwepjbs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhohuvw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixszmvf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jrquzkaq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxunuii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gstgwypi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dyptsomt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cshxndmt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgqdfdl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxeebff.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2innhcfyo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnwhmer.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbbjlhu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsuzkkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejftnvtw.html


<!-- 参考信息 -->