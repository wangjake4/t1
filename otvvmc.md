代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2npprornl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atqeuwje.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzfmkku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2duaumxls.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkewvn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvffuaoh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxahsgnr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgltcxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxfcehi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2paxagvmd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axqcwget.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yycvakhk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyliqhwr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkzdedw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgraurjg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czgahibm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwjsjcz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cipxwfov.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdmjiwr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfujrost.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrnegbf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emmwwghy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msuulcsc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyimkay.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2aednivcw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcukeerj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbosoane.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsbhgwj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dswhqyeb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgqqbdr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjpyrrr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oawdxvob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddkkgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2njwwsknp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwodilg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqndrdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrlcuwi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ofypgcdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usozsxln.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuywlfn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhcglbl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oslityxb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oibdngkz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyudosj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpsjafd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2stjddbni.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvsqtpk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjeksvg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlssygqc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ladrgjrt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhjoelf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkunhzd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fovcyuyd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdvuqgg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfqvhoc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2afyqpfnv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zktdhjnm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwvrano.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eljytcww.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2feetqoyc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2azhnwejz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2euylkttb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlckokg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbstfdz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ageiqhjv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2smlueeuk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoozavn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2azwvjbms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjkenmu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqytueo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsetlxfg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufophore.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgmxedn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wopidrft.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbiaqax.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjzojgp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuywybc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqzbnsf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbmdmbu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzryfrsp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2framxlbz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jylzdlui.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2desutwzw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cavotzsl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjkqsfk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2biqormdu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddntlhsb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrksjsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cybrkivg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myzueaab.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqhpzhm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcpvygh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbsiitf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sncalknb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrzwdk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lootjjoa.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgpoxm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgolwrw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkbzztf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzcuxnf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qbibeltb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfvyxcr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrjtkzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vymrvlbi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klviovzg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtignphs.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhcdsbx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmnnfxe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkkkkqg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brdemgrc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guhiklzl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtepruyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbtmzxj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrnbfnj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2svsbmjuo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfnalqq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuljiitw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmntaigc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpkjlpg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywptpjac.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iypowxpb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsydnsc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmuidyz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyeehzx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrizvis.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlkeekj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qsetytop.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnflcsa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsgqcti.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zfepcllm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2snhyiorh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iywmdcnr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glftfihr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wblamnps.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uylhxkyq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhyuxef.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eygxplzm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwrtfgl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtgqcun.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxkeozf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofrkuca.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtemsudf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhnllhq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihntadsd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxsnxby.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wztacoca.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkuhriq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2buncmjqp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitupytk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbfglq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2heovzxha.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2glnhptrg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qcypiayh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtnrkja.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdycymtb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cckaakek.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcpufvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2utouldiq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmjbska.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpywfisn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pklordjg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yalsumsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzrsghi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kjurchsu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2heimvhik.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ztelmfov.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjmqxhh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrcbpp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdhxjiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twwvyxgm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwqmjmh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sauwgxca.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2laeotdcc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pialszht.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyaqopz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uesnhaln.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzrcsz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryunrage.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2axqeqdxn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlorxdyk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpwbpun.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2okcezlyh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxntoyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxkyqvf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzatnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlflvqi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lglonpuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpyizor.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeztzwm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itonndhr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoedxccj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpagxri.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxsmqip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhutsljv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcyielu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzupxbb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltshfutn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhecuzz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzpwihl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdkcmut.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgislli.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfexiyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2canppduj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihqrnao.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyktung.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwrgssb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pccjfjbw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaysmjv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjpckum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkabiueb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kapuojyg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxdvrhi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eithzepx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uflqvbss.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thsigjri.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcgbnrd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npmndtgu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzrxwcb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drdcxcxk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2knkibsms.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdxchtg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awckcahe.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2viahldlg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpksums.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjskuko.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrhwvjg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzvxdmp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthwqxd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzpusfd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oghyhwej.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzugunb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mbovercr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoajgex.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnvfmyj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjcqggf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rrertxuc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2knankppd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2crlnmuum.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxvgodi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2atttvefr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2twzyuwmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhcckzh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjuqrni.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itqcqrte.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sioywass.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbhdbll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gedfeury.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbrfxib.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcytuben.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jwblxviv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsxkqig.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiqdudu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fscsaayh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjodcje.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsvzaac.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cudsxicb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zexpszjl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrwxzan.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcdbbhz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2vchlobdw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2niuvvkzs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqahcbum.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgykrqyx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoguwkp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zupijiyt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxoitau.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ptafjjrn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2luevtyys.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzunhuqw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2runtigko.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2evlspzvn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gmawicpe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdjooph.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfbxcq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xznkuxvs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2behedqri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgqdyv.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeppftk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvmginb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlzlweg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kizofuzf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsevsne.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsijpcuf.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmnznqw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgulywc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxcrcyr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxuzogr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwjlpiz.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2piwcvmaz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjugrdwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyztcrt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzswdnld.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgasimon.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiuhrvw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjzlszp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabanuv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuzpeuu.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qptrzbqa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rviqkmsb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vuebykmi.html


<!-- 参考信息 -->