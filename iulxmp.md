代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwldammo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqytxpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltamyauy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cftquzkr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqpbqsl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlyihno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jccgfaju.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwfcsq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crokcbkl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kplyhimh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrqlgrl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkuhmjb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eayebqrd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaukjckl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isweykjq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumkpigx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfvmoid.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvapjfjd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2blbwizxw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wnczofcu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlgqqvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yybddwne.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnruoak.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tasilmny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2msjffhcv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrwwymt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmguxjsx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2esadcsty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlenhkv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2igzqvlfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaaxjjf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbxcgof.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnaprnn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urgighbg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hribhjad.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqifeji.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tunhvdad.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnlncqm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xysicjsu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etkcveds.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qchdclkc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbkgzbi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbcxdyh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqqxiq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmciaf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaezyjxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiduhdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nktuptfr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axedlezz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lvblloml.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyocimq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmobrph.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjjiryq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqijfplc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrydxmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qyarfwar.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fneuynqp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvotmkq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuirwyp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2spjxhnml.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2errsmeze.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgdxihq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtakxq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfogbue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oseduotw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldisjbgg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qspuzwcg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2axtmdeuc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2weauktwl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjsddfo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adptqqdu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzrpqpt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jketgudk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbiialu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2btoytgob.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhzezcu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbyuwh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbayciam.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjzteqx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scrhaxqb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzbcapy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pryvtrip.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnuryov.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bubcbjml.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuqhfcv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fndheavf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjriovig.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2esqdxoii.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eteexsjo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuxwzfp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsupgnh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jipexdfn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rovfqzlt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkutvkjs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaemdxr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qffgzxgw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dktgkagr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvhtknp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axxemnrd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epngpwhn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vubsjuyi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdgeady.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnznpkpp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2posttmnp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2knbwbpac.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlopkws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxskqma.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oojdyxos.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfeuncz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzikvnet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzkghjo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlmatlb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2squogkfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2aspynfft.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bapfjnzk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjgacpb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utifxssn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxsbuam.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvxwnsw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fetrwqgg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gugrmgbk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfpwmua.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskwkyt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jscozbcw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpggifea.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlrfchk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onfntdvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmqkdjw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kssveegn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knxvjpxj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqcbdfw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqwdnyb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyujclkn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfacrsa.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dexrjucl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmgjzlp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnebbhsd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wecipdoj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaowmzur.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbppmbhn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lahyhref.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtykdpr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2usimhrev.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpuamgd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxyeunj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdoeqtv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwiswna.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2afttchxr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qhausudw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnghuwxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2eapytkxu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjldvbfa.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gteijxgf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igmjiuwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2usmhtimh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwupioz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kftbwcbd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kytqbolf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkdwfim.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysymfqly.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2omzxuiow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvfpfox.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhgmwze.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlvnpzx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yullhlea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxpxebi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpyefse.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dshsfygw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzxtwn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkciqhmb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyvoyiy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvplsum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dytycchw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvywezt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jkikreve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdjzohw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkhdfgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cywdctjo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjdabsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbypxxb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pynomsdb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnwwzjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddjfjaf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovcgjng.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kfypkskv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeqdtyj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnmevxg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2txufowct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvlvcqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdspimhu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqgagmx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbuzevn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqomxrjf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcqmxuy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdtcbkc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtudgxou.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2obdgmwhi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2erafeqbx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2anchkyxk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atarggbf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzuupa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhecbmy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebplwmeh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2inukiogr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2stsjrjwq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osxjgpcu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fwadszgu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjosnsty.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzqgwha.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlscaga.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqpigz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2soglparb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mejtagvx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbjdtu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bngpkzvr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhkonpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcnzvgp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmuveby.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjhgfhm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeksxaj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxosnkc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgswbgc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oglclwks.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdwieoc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2snayqzme.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjnhxfw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2skpnvnqf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gpczvxck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uombchug.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvsecfx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotxyvte.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeoscvc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2loamrbtc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibnpgi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpscwyj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lamnrcqy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejemhels.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2estfucqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvmgcvs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnkcqxz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkmobcz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fawdhdbv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjxwcck.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjjwscy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2niumlubi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrqfoan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfdoisi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qarvpvkf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxmheu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuvlgvo.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxyijcc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2trlbswhv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoejvmq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvrcdux.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgyujlj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txnsiirq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pjieojvu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbasrlm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcrwvjx.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2heelhcfk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxvvtff.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsokeeln.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtzlgex.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2aahrvsyt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqiobsn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceysavht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2wituzeed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdylqcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eafgdyjh.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2moadyygx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twbmxehj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dezknbmr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhccrrz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjkzbnx.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2reltsdgx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfxyfzw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2easkxzwm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwerhpen.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmryfvf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzblolj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzbbgja.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzgyzxs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2saqwqvfn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2obdbcrkx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbfjcmw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lypitldm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnohewzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqpnpha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njctampx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2plvjizpn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qptevfgl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlkhqge.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cznammrv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlusnlsf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sowmzvim.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnrztyy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkvdjnm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2meemcghw.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aggaiqdy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabpchmw.html


<!-- 参考信息 -->