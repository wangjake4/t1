代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzljvo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyauvmr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lplisvut.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sejjusre.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gponutlh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waptmxbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vexltiyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2selzzltp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktxfymy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwtinwt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2urerxjpf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2arvhkhkw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmohzco.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzudotqh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjfbtmv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkrlsgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmjglxx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtfccic.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjpnird.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpepmkh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofegxttv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrhmdhg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiampfso.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iexoomhg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msqktitc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqklqemj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfyvasa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyijwpk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvahrszx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjyjhqo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmubacek.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvufuvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcrjmwj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfabien.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omiiatqi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfinfygn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hiurtbwh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suiaqptn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqshskjn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sbugxunc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfvoygr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gbweiyjx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gidnounb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmtobxj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzfckar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfvqdo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqmrhkx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2abucdkga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcbhboc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfdpvto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxjucty.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlcciyt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uywczate.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vweqzmbn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egzhqwuo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvnltns.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyuxrgx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpirgqc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrybbdo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvjagij.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdnwnuo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jvboxnbq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsoianc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdhscdx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgmgykm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdonumcq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tseyurxy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uegcgotn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxbjllh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2visovrrs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iadyuyve.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbobtc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfpvtdt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpjlqbm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvtqlzn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhwcsdi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjbmpfo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdgwipd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqcjdd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdtdckr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdjkjuz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfwqefg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzcwabq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdcszv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqvteus.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npkrjnpd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsizzgvf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvqbstx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvatio.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrzslpe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pleuzbpj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgllxnvr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbarxbz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkqxxmr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgaizsp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzsvlxb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oibmaqon.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeuadbx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oondcdol.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeefeyqd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrvjohb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmhzomu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxnvtq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqewkcmy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yevmtops.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhqcjid.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2srcyytgq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kafxlkng.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2igddzlbq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmzzeny.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwgdnte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtyndug.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgowouf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kurjnqwz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvjuwgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhwmweb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knxyelsp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azgyingw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwifzcq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bavahvyv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuzctlw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpovjvy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iawvxibo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvtmxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrzepfp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emnnntve.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pugubwzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auwyuynz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfauuzjp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ounowxny.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyzlsfz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yepqhqdk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxmlsia.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvxdha.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhzifuf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrugblp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wofnkcip.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwblrug.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdnlczl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnhhmka.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pibtuenn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2unyuynyz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuewvix.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uspvowin.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuitwqgz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myoqvlee.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdakbh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwlrjgy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2igrwfogs.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szythxqq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbwfvw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2exiuajku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onrilxfo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jitbhwnn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uifeomlt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxaycfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbgugou.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifldzken.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgsjdmy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lewzyykk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2efhnfiqs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2whucvupw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqogmat.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvrkyib.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bunwvnfj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpbulwl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyikvns.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnrzgcu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uthpdivt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rslztejk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ppekaikm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbhoypo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsbqzkh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwetwmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvautggt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oulzvhnb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfulvkif.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbenekvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpiflaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuivlul.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvimbbr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvwvxhn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcgmgrq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfzqmjp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhnjbwc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvvqqws.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvvfjgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhwwsoe.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuusndrb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etajigxc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrqiihe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbydbylb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvcrqzg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgcufh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bxergqji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjvfuxd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2totoaovv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifndrqwm.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfrshvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhlqmfu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpqauwe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsiccba.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoltfex.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeshxab.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ssntxhav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkbgzeg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxqgfsi.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwwdoad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcriijyp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxwyztb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvysxoc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwcrozp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjcjhkw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nrojdkxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrrihtn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbymoy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxrrorp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncishwao.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmpjrst.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkcoeen.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2epvlpygi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iieuikpe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucniixpc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2krgxskrc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2suzxhexp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xloixxbi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoiyrop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqipqpow.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqhmxch.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjqvjsg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeujxouc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvtguuz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvbxrvn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyappqfk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tizokvnq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zyviwlgt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gipwypsd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asasyuuc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhfbbsp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oayzixdn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqzafwc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oskehygn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsslqwb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvwfsvv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwtjomz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rarsstzj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvpumpi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnvrido.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgweeth.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbntnepl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiceetpc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmuybda.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gznbiyhx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjognzhn.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrocgkce.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imimavbv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppycsaph.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tldbcakq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhmazuv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oaitmcom.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqielje.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ovywyfrv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyavipkn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2odkflurq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlsiifx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopdgpyq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2flnfqiqv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyazapg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qossxmwm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2atcuadyj.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2meekgyvn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkliaa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdowvor.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqhhlty.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbmmlou.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcajaxp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwuvvdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2elhqcmfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsgfgku.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2azxystwu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzgqoyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxegrueh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnhviuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wukhczlp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uhawbhlr.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2blydjpdr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdcjief.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqshtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtorlkn.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfgecgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkslswfs.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2szjbttrj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhnsrze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjliypgm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyyxvks.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkeqawn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtlvpk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2czioygwc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyyihvm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvfvyhw.html


<!-- 参考信息 -->