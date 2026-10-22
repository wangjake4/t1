代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhvzoh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhwluoy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqitsx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjssepx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cebwwzln.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2btdrczbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfodwls.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjzdaxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snlqsowc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfidoyvn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xquhkvbu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyocwxfo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjrtjfa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnicjnr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jskbxvij.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fttzimmd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxxxwsg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnlixgl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvfjtyl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anmrbrvl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2alizjxic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtspoh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xirpbpnu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpgrswi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgpdvyi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtghrfo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuqukgn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnehzij.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcxkdhd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxucmjl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqsyjks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlkbte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whxvwcha.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhekxzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjztyzod.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2imviskko.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uytlotnx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byzlvpeq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oebbtefb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mptegeoj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvflvtg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkznfvcu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlozabvv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqwtvui.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wswzyxrl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrmzcot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uherkpfx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxtdojc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lunqdfyy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkgpwdp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgewpat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbftlzvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pswdltgp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xmswhrmo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qofcdtin.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnujcgl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvszutv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2falrrwdg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2owwbwhsp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zdatxlno.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiywnww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkdtgmq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcbvezx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idtaulvb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfdxrvy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvknyapg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqegzuwl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phdrsdti.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jimxmvmm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oefrkytu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiurpaxw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqczfb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdvbexs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpounbd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsalflrv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rseiiigi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyxpcns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtwvlu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nypmntph.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgzokpl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbtspia.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqnzzet.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtzdfgb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nirmokuw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbsrcaj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvqbsxz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ephvovju.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elwopnqo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdqrrnj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2imrsbauc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbvcbhn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaqptpc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjvsqka.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqadfd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyskxury.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xybpiepg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2konqxiwd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2irjsrrcf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yizeepet.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmmofpd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egkmezls.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znypkcxj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmfzxoa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwcsdyk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojljkkmh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbdzkou.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkodjrd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ompvacaf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vyndlhky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzstymc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhrzsgk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arplfquu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bslbltiy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlnyzar.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2forqkurm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2symjgkew.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkzwugp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wspqbwox.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgoxahd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkdqbi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ssehjhhf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxnwzy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uaetlcqb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nrltlerh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fzslscxo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2spdcunis.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzlmmci.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiveccd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cffbsalz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teipdnfw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsokfqs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrdapnl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2icgbiegl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziriykro.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czmlesbv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2blmehyyk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpsaajk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giujihps.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvwosqq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yucecpzk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrerhvf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhkyhqt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkelpkmk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vefiwuca.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhktytw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hlllbocr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rlevgblt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zazxabxh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uqczpxdu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2irmysvhk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclvjtx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaxuzpa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jddtdtub.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xhivqxyk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2adhrbfcj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhjjgrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrpbgyj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljieliwl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgviupqq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nwewtjnh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzdrein.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbplrub.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2duorfjih.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dplstjya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2icidrdyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxzuaaf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2osjqcwxs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqkxupc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kueothgj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oetnlorj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2njhzmvje.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhsuypu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zamptqeh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqvnczp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nblrqajt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqfwcsh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcbiszi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvajaet.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ebztokax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fncujcos.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wfguoidm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2decaynug.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pzemiiul.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zadcazlx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2widskjqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeygilxf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthmurqs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqnemig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tobotspc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqtusnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxevcynf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlcfyry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvjlxba.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvinbuv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndsqit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jytfkqcx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwobqnus.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaccoja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgmnfkt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhjwwzu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpuoicb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkodzmgg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fblzoocb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2swiusbzy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iogfebkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aidmislh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2izawvalj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2srzdblej.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2warrmasb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jyydgjhb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjurmoq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjmmamq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkmqsyv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iivtrrau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmwehwb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2krphmbfl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmgkglo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooudvldo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upjvdqpo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxdggjn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxlscbv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnegzvxo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcciqutr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoanxur.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrfswbh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtbtbnz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyandhd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvsotps.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vylmgact.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yldireyx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhazsen.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkovval.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2isiutucu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuoiojd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqucvmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2avhjfxte.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drpyoync.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2apinnhta.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjunvvcl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmljvhmd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxtyure.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rcusjiop.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hzchxuic.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ihepzlyd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlismann.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2whilenrc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhpezyz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtftgyb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rogemist.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkontob.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzykoa.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvwjnm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vtniqvpn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdqflsb.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atjgoosf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdvwtbg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtzysxz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuhpfbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjpsshy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rumdaqhf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkbihxz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2msojjhql.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfwkkmp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsznckt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhvkkzt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfjjqi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2muhhxmip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dviswbko.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwaimvx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqwxvtb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpgswfr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rypzxoay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovchfxdx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yizkqhsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzssdmnl.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaqgihp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lalsmwkl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zstrpbkm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmduabk.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiagvhrn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnopqck.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2knagmbtu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiaiacu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfocnv.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpzfkky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycrrkgt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2djuvqhsx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2njpfluwr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfzems.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzghlvrj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikkwulz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudnzvjo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lneynyan.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2efvvrfcm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtfauuh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzeajsd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzrtsly.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lecyefnt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeewddf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqenudz.html


<!-- 参考信息 -->