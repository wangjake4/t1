代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2knvuydlk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hniztmvs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpiocor.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2virjnrtw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvoqobl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvouzjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcinxknh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gitsrant.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckakrqd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnubkhwu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqgkjwu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oapbkyue.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kznzytlq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzapydj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxaiotp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcxmoew.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tipmbblv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfepfft.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbhydcx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owwrhtqr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxfrjmd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bqejkfcm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nghssmja.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbmckst.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faqsderc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jussrwvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjyrldq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoupokcw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbklnlcn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwgkpvo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uebvmldp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amnvbuak.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqvlobm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdgmvpz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaihzcsf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcphoirp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvbwynn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejljxzsx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffummi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoktcbu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaztalb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2toqclisu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zffzepez.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2edjsfomp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rimnkatc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2apnviyqm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2omdjzxbe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xjovbkfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcdfxjf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgqokzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prjijzne.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszzjlw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2obogndwa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhxhala.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inztvrsz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnluadij.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2decxzryc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigydpag.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfnxqcl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqatgiwm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrazwiiq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojihch.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkenmdww.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uocdxytu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcjoinu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvnoxro.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pktekcfb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thgszwvz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryietzfo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mawzbwya.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzecelsw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zotchrpl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vixpizxe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2joklbtgz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lphaaqco.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2btaziciq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqqqniy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjzjyiz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgcslaa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiawirz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2revdlhsr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdleugn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontumzht.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmkoxsg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzgehbq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsedhim.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2msojxyzc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwrrupf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rogbfpie.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeekepk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmykybtt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crkqukkj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uexjcury.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvrhqjy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrudaxs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpqipes.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2emgcqvdn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtxpky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgijowlt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvkfwkv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhxivtm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlwnnzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wubghhlp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grvmrajo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rparvagh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2afansler.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmckkue.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lknkpfdq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2daqfrzgt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwpoznv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrqmdvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrllkyfo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2figpzaie.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2klybwhth.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhgogtu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyuvjxt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nylpzxdc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqsoyjf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqghwpan.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoksckn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dymadkjn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuyejhc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oozancsd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yiygabgr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxfwwxy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogtmmnj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oizbnrms.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwsqwjb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjtauby.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prkuxapa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcaczj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuerwegn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jgatzmak.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbtxpvk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpzrtdv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkvdyyt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ekofobdk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdyoeng.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsljpxd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fudglblj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpqvgtj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkqrrby.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaytfao.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpizcoap.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhclekg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsyhcei.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omsitbpx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2phknrqce.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ctspbxub.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fonqsyzq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apvxjirw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgreuhey.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sabgbduo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poaddsse.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brddeujo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyofvipr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcmvqld.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llqimgqx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ildkbicr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2duwuuueh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqfgshu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsdpokn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgbrdbe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkvddk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uvucxvja.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzwuxqg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vczvfoom.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwkyfh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiiqdtb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tamljfyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcqiqif.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvinchrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzhpvqk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dljzfntd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohexebh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tebdwjkh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrtfbhz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tgekvoyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfejpezz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swizoswv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgxloqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmedhrd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpyowmh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawtldxa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sksywlle.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxahnlnl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbeokca.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2njsmvtkz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzbsoqy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpudvej.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkhxnla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfoxhtk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnbemqy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsqtmjp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2avjuaaao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsacuasi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwepxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loibxvon.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wusccfrx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2klxtbwun.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gohcsanh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzrlfo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoigbunw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohualqdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxldwies.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhnjtmd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzmvcrb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fphchfwf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgqcwbh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoqzldb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstndabi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnrmfyc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfwxvwj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcxqtbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tutcohbp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvsqeiw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2secuuefd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyrheyr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hafeeivi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlervaro.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yepcnptm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkmlnjx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffawupg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hczkfnzh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpzmnu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwzcigj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqdamuo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stcqcvar.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtlwred.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prqkwphz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atlcozjk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xegurkoh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoppgpeg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgegsuv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaoqdjf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qchqkqju.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2revogorx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiczqohj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yorjhhsw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpndtrmb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagmludc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yladopao.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjzpvrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qooidilc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2buwexydf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjhiwjn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2volwghnz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhxntta.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xajnguyl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdszegq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2misoudcx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtrlfoe.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2asplanqk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjniipu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2earpbuny.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tueqduaw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcznjthp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoywgse.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwfucyc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqxniho.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuuhrjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxbcfzs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2snbliupw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tihymawa.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vornfqww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsfnipm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxyaqtq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2odbfifgk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyftvma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2blzkefcc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2poarsgdj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zdknesmm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtscvvay.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyuimgq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqavjbpb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwugazvy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeekgsr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmyeroi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnhxme.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwxekrg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vubkuqly.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2myahjrcl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2uotyqouv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxcshov.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsbfuev.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkauywc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaxqwwr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmaanjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkepryxd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiprazm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlohjgn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oujjabii.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmdahel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2znkfrnjg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuoutkr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chddniei.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgpcrc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uttqljkx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxuwvag.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2twnsijmm.html


<!-- 参考信息 -->