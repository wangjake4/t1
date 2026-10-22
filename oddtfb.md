代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hizqpyto.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bosqjpnc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaqwceo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcvixpm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrkvmpa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhfsfpg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtgzmnb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2drtvnily.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiytblhz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpzyopj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zriipkrt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvtuayv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fttmbjcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfhiqp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2khedvphj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vquanxfl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooalgtic.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqlirzz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaxbkbd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaoombm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tgogscoj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emyvaiql.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyzwngf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2znhsauyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2obnebctq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhehohe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtwzcpg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ickxdvck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlebrpb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqzamxp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iniloufc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fleidlej.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prunweuq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncniblre.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuompzoy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdazjnop.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exovxwtj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2beawxaxz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txlazvuv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyucfey.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvssgsco.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvegjkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kanefjur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqfwowq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mswehfuy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrvzrqc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlcuofs.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yfktpjbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pluudukq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2emhiuznv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qeemkmdq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbddpna.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2iprjkoid.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fomtfhdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzucsz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujkjiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keshozyl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfbrckz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hacfqmqy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsprhmns.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2citapelq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeusksj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbmciy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yklvuend.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsgrjzr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesemum.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqiczgr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uauonrit.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgnbxfl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwghen.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdymnxwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lskabpex.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkqdtmz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpdzziz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybueybpb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnevon.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lapxcvyb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2npztkloe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwvkugy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzhieet.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2igceeyan.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnlhwuu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbmrgpz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzwicbq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhrbbmz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoklved.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2psjkzlcd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2klvxabff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itccuqyq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgdldbw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbijkshj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vasaqwqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2unpszlhb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msigopcy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2exlgfkja.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyasplm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uucmchsd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwldwfjt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nripiaja.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxztfela.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xejmzwxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlhcxcf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjlcbnf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krjhlesi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdffulvu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2epukfozd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhagrrz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpdycjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbvvulo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjzcgje.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tvevxqto.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dajkfdyr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmltxsh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mksstfrn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxapkdk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2azcrhwzq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jokbtkzr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoepsqu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vshruapd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2anwjdeqk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkxyepu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2madcneun.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxkbkbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2twuearqp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2micseoxa.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exgexdcl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyqdriw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khjwaqyh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eewpsabb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgglpeuz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrrqyrj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tuptypiq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpcwbqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhodjgnq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoskinc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eksfonsd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmedwpf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oksbskfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vddvfkld.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkixczj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnoidp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pslalbmn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gexzuxqq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2srzefupn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2evpigsal.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvskoia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2krqkbjyr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwlvaof.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqqkwxt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xawuryib.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zslojbmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimcjgoi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jddjahsh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdvoudy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtzcjtu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzqckjz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvdozen.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqoermm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2buhutsrn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2coztwdie.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzjelka.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhjviwy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqhjgol.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfqncrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iamqulfu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yobxcccl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaghleh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpndaeqa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqajheb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnweelv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkbduqa.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdnunfk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2derpoijy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpljxdi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvsmtl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmimrli.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zniywbet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpyyfbd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xilrolnu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2alykusxd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmyfcmd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkakgcvg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopituj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2itvvtpxb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ychvohgp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxioxloi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pyksghvs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvragngy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmeyrcx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lythtmts.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwfqsxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsqkndv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jspfvhga.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhnvxtj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkxgyxq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjlveej.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbodpek.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rolierhn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyszkulm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbsvjtn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fouvupfz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yingpqlk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwcvyas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suijrcxl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmbmcwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apffkpbf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbiywlt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfqczfi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtglbdc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkucviy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vosfkegg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzemyya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ymczziqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2swommbjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgsebxg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvqwduz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdpujka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaqvcoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmhbeue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2feokxgki.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjjfpq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2frbzocur.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwjhzoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbalfraz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2koukydwp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2agoulhzb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzhgung.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdcctbj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfonzvzj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfezlmzo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhoqpqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2trcndyyj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqvckcr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdgoyix.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnaitem.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzenqnt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrzqkbj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgjljmw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guysoocp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbshmle.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsxgveb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqqrgvw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnmcbwq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zjidkmsh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvlact.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdzulmb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhsdpdm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhrxxus.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuiyxcz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2thwhdchs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdgmkrj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2clthmnqs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2elvdyvfk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzmnwls.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbokkvd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tknbqswj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uykyzccl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2enrktvar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxxszri.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwydteu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuxiqqx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxcduki.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stqcehlf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcuunyl.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqxbpm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcztzqsk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjktwgx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xmysveao.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkzzhbr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2asdbovrz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uewztepo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhgijg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2hncjedzh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwbqhn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hygtgsbw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2teqizfgq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sgczastb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvbqszt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gljueexb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uonjbpeg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2giwrdofn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sojekvdw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhbiqjk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omwotyur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2krggonyh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nazgrfsb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2monttnix.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rltlwpqh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2nonrrwps.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2scyaojjk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pptsxcqm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyouucb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2sspqgtpb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkplhwzp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbteoyd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgebpkyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aweiievk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdhvhmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zexdexgq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbaoksh.html


<!-- 参考信息 -->