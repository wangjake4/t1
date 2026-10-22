代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gacdwbuu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hamnoprr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kclpklod.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpnezaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywafbovr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqynscou.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hehdqbyo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brvsdiuf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyvrmhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfnhqzo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chawiklc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffnawiu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnlejww.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsqhdpb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrokjza.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vpekrzuv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndgqlna.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlyhdau.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wdokizuu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2chlyhpad.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mimxwran.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gfytnlfq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2exfeymkb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmgwjfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dunsdtbm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mstuotne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swktcuis.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oivbpawe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrcmpaj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoneifih.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uawupzxm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prwrmrdh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvscgfka.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkyletb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdzvzth.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooppjtim.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxcqtl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndwmye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqgcahs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pumtzcgd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owkouciq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lahjnspr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkspmmgk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jktwhxxj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmwbzup.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjlqurv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxbcjzt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjyvvso.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoqzrco.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzefysyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tstchioe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdbzhmo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmywolt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxdajiy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjrqphk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjejrnw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqpfteh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imsadttq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gouwbtpx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slpwywas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjzptlu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlhbrdv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czvdxaog.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqrxcej.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fopljgvc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imizyseu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnbkynr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrlfqyb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kknscnei.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ychlyiov.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdemqts.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcrusjn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuouxrm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiojrep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvpvtk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czawbuwy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybjbysb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuukkgft.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nodcinvf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oponcynk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyzdvbk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rltukccp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyajyhog.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2moxaktcu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srymttrv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkbescz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnwmysy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mkikejsv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqeciwl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzacuoz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kceatjck.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrzahlu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsijvcb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gozfnzjh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijknwlfe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlonzive.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvrfvxk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bngtxqqz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdmjlsl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lmokjbjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zlctjugm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoyqpbw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmeexlf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdajeuy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfeabde.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkmmxie.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpwvvfe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzibxmm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iamnsxvw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnfxtsc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvgdxue.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zykcotxn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rqplmdlr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2chwayryo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2onbzsgig.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjokiyjm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvwokbh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdqvvhn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbsquzj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbdaoif.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfigmtqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcilgvr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajysudu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqsshuo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmojiulh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxhrdht.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnezoxp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyilghp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsdsfog.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkbwhao.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwnuaqu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqivycc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtiqifk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfixxvv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fagspoei.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nepacbhh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2beoezxke.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlqeays.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2twhskcxg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtnduhh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2udlzvldt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrdkhhj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gykceiti.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gunoaglu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xgseijtf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2klcwjcei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjjplca.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbomfrlb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmnjjeu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkjivyv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulekhsp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybqybd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmrgvq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmnhdgw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dpagklgq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqtovwg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiokcqv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecvptdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2siipbcat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsylvli.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyefzbc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrtqvv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvwobeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmveloo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2votkhodu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrwguuv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhrflsv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrgmnxb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoquvwl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cocnlkvs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mdopmvsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbvjcwr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcqkfpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvxyqor.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cnirqdof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyylxzy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlgbxfv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyklewif.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cstqaomo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wezeqnwr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpnkyyb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmlqsbv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyncvre.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqcljfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzuvpnl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgtkvde.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2penejvwi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdgqlee.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ladadzci.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeikpfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oloshiul.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2toinlyzq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyvewde.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpmqxrj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgzjaoa.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vffvdmiz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxqnamr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qveggjhv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wamucgwg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtcetia.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxdueoz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mieyhzcd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2saakqtnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kseufsbn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abklzdtn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vctqkgwj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhswosz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kznayovb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2noflkdko.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxfqbew.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyspufo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvpvmys.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrfanwq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfaahwb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khplztge.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brdeachn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvqqvvz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nwidpgaq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyiswly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2knsiqpof.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgethrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagnjvdv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2blzltfck.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdnhzwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jejnljzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffomsyci.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcihdqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2snwyzynz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2muacumia.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhorwost.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemvoqms.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfqxkfq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavgyyq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpeqfmx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcsybci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuusxwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exqyailc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yndsjjgi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzzasmn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuuxlfq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmqbysh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciembnev.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwvrzde.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmbtuyw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2okhscfwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2acnfgkse.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyxnoun.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyddjdy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fexyeicq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqkvozi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjncwhf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwxxopn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcitspj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpjqmlq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgawkwu.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfugeiw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbumous.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmzxju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mzssspry.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2aegcicsm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zureaauc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyvcdep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetqmfzh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpflwnma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltskmgco.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enyhkaao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jayvpyxi.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbykfvea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxnzzhc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2suqlcuqd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2remfipui.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtalbwl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuihegx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2njaoosbz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmqmuzs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrugigs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tajdemts.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpknffv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlyvrai.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2typgpyhg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2twwhcnsq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2byrqddsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskmfftr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nujrvojt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yisfnjab.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2muswftvz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbbrgys.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlwjish.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bivdsrni.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wljopzzb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvftrhiz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2gqinvrzs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhwbzat.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2tljmwabu.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2virwwoni.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmvkgbw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yznpyama.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hecqgmql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwxqijv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdyvwhy.html


<!-- 参考信息 -->