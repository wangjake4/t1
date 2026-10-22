代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dojzuqwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvuidla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoxzdok.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxqbzco.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cjewzkzu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2srfcopyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdabst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbuvie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsecmhts.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vllvqvrw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewghwnwe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuolqjid.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bskhrtls.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgvhpxl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzunuojs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhketumq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicuckc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajenigat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttschqgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxzjohj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobohdv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgpmwia.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaxmuwq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tufbugbk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqgoxmb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxfedkh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdkeaf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jswnzsbf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqosfpc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ljncpbdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2entryqps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hyioehkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udxjscpi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oojrtawh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsuytkz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2thhpbeng.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpwfqod.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjsbhtg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzpbzlq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqufsiaj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idyauusg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsjjjsz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lowzexoh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blbbiftv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osfidgmy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wrimgkfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2debizzcb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npxfiaii.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjierauc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkpiqgk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhkdfgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjsbagq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uemcbcbs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zohwvhcg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaazvqo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2itwbeune.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nquobhwm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkpwlcn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrlbwxa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxlqqgp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkglheod.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2awxulmcf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2asmlvfxi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgrfjzm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isgxvcvk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlaegyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakkzkzo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhgextb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcdihch.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uobaagno.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2thuupjyk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kmftwceg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxnazen.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kebpclze.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmgjhta.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svozdmrf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boxjojwt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jeswkzyb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vavfgtko.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwbbhhi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkeanvz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqduwhi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuuabin.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqhlxxm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzsctyg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgskfypw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eoacwdha.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqrhltv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhumbbmk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fonaxcxo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbykllzp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2btwbdmlq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2alqagdmf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xasengex.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdfanle.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvggjidb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2slmsbdjw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwntmoo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvenszs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzymim.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkwsqzl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvmcdm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suxhvhcd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2envubead.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwnyslo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhqrayr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gskugwku.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcchvvo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbxjfun.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwvjdwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmdfbwh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimzbey.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkddcpbe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxsgjwh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wiodbdhh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuppusq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtnzskk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvehljj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrrsczk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuocyta.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqpumdl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rfolmivr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tnemupbh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjaotsi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxdltr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbxryec.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfuihzj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pffborbg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oriyslne.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkmpbnd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clyhkgyw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqsdptj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgaeapq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otfclqjp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyjwvup.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oskpartf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjnqkxc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tscbynfd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgihcfs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czmuwlnx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtevdub.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2onjxqacz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwemncw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zozytwzy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvfzffu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2itxagjdx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhnrtfz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bojubmlh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2occlaurt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihsimp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpvhlyj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dhevxhqo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtltesv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzoxzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmksfdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2twpvzjch.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsstazvt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvcwtcm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqmqmca.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgezfns.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvltkcju.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2adneluyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvirfur.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxlweso.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuwnyiu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcgdsxg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2anoikuxv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrztqflh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kffxrtni.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsmczle.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2huqzjrwj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfbngli.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2teoqcqkj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvdwjrr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksymxihy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnxgaoo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2basexywy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyxuiwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdezto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfevebq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yosjhatw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avgrezbq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2igbeqdrc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwszxsya.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzwohp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqwaimp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsudquql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djotuxdl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xowtkpov.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdfxzqx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpvruep.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxkesol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2udujdidn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lutjkyql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htfrjfpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qskateit.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nawhwcfj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbjtyyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfnjxom.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvgaxrn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrfvyig.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2esqwhhjg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fylqkxco.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhtsqzf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmkhmxq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdbwwls.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2aodvlmgr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gutloelh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2suslrfkz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgjwmrb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqnuqzo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azxqkvqa.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwvoof.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nshkhnrr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2torlqses.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhgrksl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pojftumn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnimhgle.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jszscdos.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2sqckghkr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwdjdxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flqqoanh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvqpnxk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnemjdou.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaecgvyj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkdytgi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoibbnex.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcdukfk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgyqrs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aazkpwll.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbzuidh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqgbgm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfolgbxg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwwyyor.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcklmmft.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xhitenxp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsewcsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2peqfblfe.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkghexnp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqksoau.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcemmpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwatuct.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfnzirx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xanrgowy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbyktum.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyqafil.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fustqmfq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2umfldkrc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yynyamsr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxqhewj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlthvijz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mynbdupj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aamvksxt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhitxmz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyppeef.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2patknicz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsteqsr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2egmuwozg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuxchrq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkemoamz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwlacqh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwxeqlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2quhshbjq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kezudzqv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmabyzx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2olxkauxj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvxxsvq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wocollqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2koqtmtco.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnxbnoh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzuurqh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2htudtfdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayudvmvl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ugauoajz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfsxzpx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hgitxhfl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxkoedi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iziifiwn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkjmzbf.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2naiytzot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlinfrx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgysvqsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfypnws.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkyxjep.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijncfvoo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofxykvf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrvekw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgxdgx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogbuhfq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifldktbd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabovaqu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmumkiz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeefmox.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpsatnc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvckthj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqualjc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhlfbpq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyusyqpk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2swnpzfow.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlgmcua.html


<!-- 参考信息 -->