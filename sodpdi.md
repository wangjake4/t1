代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfxlsfy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiwwzij.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvpesef.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zoioyuae.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyycbep.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrvcduk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2glzclcof.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyoqmnz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ergxptgr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vemswauo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bejvqpkj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nykahjdg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoaacqg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uufjndhd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmkjrtq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kroqidny.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akfynlqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgebfrx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxettqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qilfnoor.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbmogsh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gofubthz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxhrdtk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpnrhxf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dflbppjg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiirnzm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpimvkkx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmjabwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymikdzj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zruxrzvg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxzbldk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2judfezbo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaxeaun.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgfkhbi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikafkmbh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbwzpdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muifmlcb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtbxwgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxlqmpi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwrvudm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxzdrow.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csmeysgv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uevmoyug.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpqiwon.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfergvqs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nolwrvpy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jroncorv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scxxcghb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmmkfsi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rkccgkch.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pndqofrm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2assjdxfc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsnkmeu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vveyospa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwiegcv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfgrkjr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkzydhd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhyrwce.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaxwmqv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnlqrkk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfknuayt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2czonctrm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2shbeedos.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlmeegp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvapbapl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbcwkxq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2thaekyms.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkuwcsq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzoiuci.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nznildau.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpverew.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qilotawd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbxhxem.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duagvnwi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpqksuo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcusuni.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fypkpdlo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qosbzhrj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uavzysjv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bojigwjp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chcxfkpc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2duewtxpk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzlckbt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haazmjyw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pkplrkuo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2knxzrcdu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bemhostl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qssapigh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkekgyw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qumbevjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qogcapvv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lddbdupy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnagyfi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbknzlk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkitzmdh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtttptbj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlvnuci.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxepnmm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nozbqhnm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtbyehu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kqetupgt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2olkduqza.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeulitr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtnafxc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzffzek.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpebvhj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoogdlm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmgesii.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbyuntv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xczxgevq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vksqiidw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zoanuibs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzvmxsu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcwswva.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpsauom.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcwjlvm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsnblxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2soaaqucz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoybwuj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kowdxika.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqwnprx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfistuvi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjdvnbs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpotybe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwaifqe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2edngvvvu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sovqwdcd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ruixmlcn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iinfvsnj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmnsnpc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyickng.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntylyb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqjnzmj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtacpzg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbymfwlp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsqweuu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwuqktd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnimguha.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxagqdxl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgpytxp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpwfluy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dscnfsvc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpvksaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frtztvkv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2puvcnxkc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rudwqueb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxucsikq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrewcff.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmqefks.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncryfy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kiihzvgx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhigwds.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hchpqrfc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwznwo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2owlhwmfj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzotrat.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhuiqoz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgxaupi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzoyon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrmvgvc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2amausokw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoohjrr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnyxarp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjktfro.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuogqzzc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2caoficzo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjtveof.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndqafio.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yipqaoar.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gueggukp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2weeilbre.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2atdbhxhr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaebija.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxmmcaz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsndgeh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ivskrxkg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2khppjxqo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydpdoyc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxmwpxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlocben.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbygsxo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqvohxx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfwsgsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aejyheiw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjctwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqwfzg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsgwmah.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzusmdla.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbdphcg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvaoolx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iicbmxjg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhriveyo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lelhzrho.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuulvzp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxpqtuo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjqoevs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2epaudleb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnpaxdj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avkujlod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfthsyc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlvmqug.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2djrmqema.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymigourf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrzhib.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfkixq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvamjby.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vafinfvg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pacoxfbx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2muinivox.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxixgx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzewlht.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzmohml.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lujovprr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzbuxce.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbfjafe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urifazwa.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjotcpur.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmswhnbt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fouevehe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2luddhmce.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujosbl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nceeetdm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pylfqldl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmyuhlm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2peojixuj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rchcyjho.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwlrvy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwtzaxu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhulbwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfdgjzi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eizldfqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbviamm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rcojezni.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzteeft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2penvrstk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrkshwq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblbqdmu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiapojnn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjflais.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2anadkkeg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsxjmdx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2eytfomwl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpclleo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2moljgdzp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaufass.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqtuqae.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvjhur.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjyerjs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvowqhtb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qhacuzft.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2okbjfkzs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2anysyzwe.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2buuxrhre.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghwgtkw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuaojfj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcinempc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qpervkcf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbxirq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcupssl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fosbymuc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yscyiqqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qstemdwl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmcsvdl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyibtpkk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnmjitq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwhucre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2osvjqhzc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2awygnejd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2raqqgxst.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2khwyrfsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qttrkfvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2omqaqive.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2eaazesrz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2pftqclpa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2awexaidb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2koumeqgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trmrzftl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbqalr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcsdopa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivldvcjw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtjwwji.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzxwmco.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrlopvk.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyditgs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjswcwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqaulwc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2avomcser.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqqaciq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiwzzxa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtfhgnc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lecmfvdk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfvyfgq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwtkzkk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmfrltg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqpqzyo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oilkzfns.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgvaukg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2itoxxmed.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvumnezq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgafqjel.html


<!-- 参考信息 -->