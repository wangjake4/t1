代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnwkjmz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmyyjer.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jepurzut.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqyugbf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wboisvsi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yodnjdjx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2umfcjesg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgiiauc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoemtth.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetlxhuc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjicys.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkjoilc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrycrpve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ripjgsye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yipsdzng.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqnhgv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bynszdjz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqopzrwd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpohgkh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkkpdnb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvnmstm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaujsrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jemqbwej.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xyebknml.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkekoxk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfnaqjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yleojnra.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nshedysb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2titfsmkh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbehnvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbezxtsk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkkuajg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jmluqdng.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acjixxhe.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsebusly.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vngjwtcd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bakcljpw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvspaepf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxrsjxa.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tftsowuw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2liiphnum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jneajorq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlcukys.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbmzedf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyqkatb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsvervq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2knatzepu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwcnouz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgppcum.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxfwfrr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxyebsv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvfppvn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgifvfcd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnawytz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tniuhsqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvdmwbx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbfkvxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aarhcwci.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ekouipvw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsugnnq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyfpzcf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svawgsyt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpneaggl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpwnelq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyapvvj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phiylcky.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zooveenf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sslzfihj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uqruxwmc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlxrymu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqezedgz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbipqat.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lonqplit.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wldoamqi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyhxeur.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjjuqjb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmcfgjo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2frpxupfh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnpnlpp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvsvhwa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxomrgnk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcxhndk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqprdtqg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2excqndmo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjheqex.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtjabs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaeprel.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mafnvipd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdckgagm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tguhqdrf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mviheecb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmfazmp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjcoggr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gddvpiwx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2covwbrul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2odswztlo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkejnxg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmlauig.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bleaeqwv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feaialme.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wphqnurk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rucftihr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaabqcd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpmjfys.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xfloxnuo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbefrdo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2baelhfvn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mslvcact.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvazockf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmjycpn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2arnmzpub.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpwkpyf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gorsaotd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtbqeua.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrjrniq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kabxxxqm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvztvqt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2njlucvlw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcfxasb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2leeufvor.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfwsncp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oxljwmay.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ccusbnlk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpiqob.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luuzyaqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqzrfwv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvztawt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkssped.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbctfui.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqvuzsp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcmxagz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtiwwhi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrydhu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaunuke.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abrgzlhc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twpuevyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqtrdxl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrzfxwh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzteogha.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjddyudi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyupnrlz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsjanbr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tiocsrco.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsvhsad.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpttwbe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ezylcezx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zroczceb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2skzudmhv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwxkqnf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfxams.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2appxnibv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcrpecv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnaidfi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqynzik.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdyszpl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fatsyzcz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxyawiw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgiptct.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cyftmurl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awhycqgf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zwluqbgp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klxlgard.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvwnxcl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyqrawp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2edltrqrl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgheqxye.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvszzun.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sjawsqmh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hultaqfo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhoehqc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkuxrxd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yecpbugt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oafbxtye.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbuitxw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zozkuwju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocddrgvi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnjvupy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svtrjhqr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2irnjhbow.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcpaqbg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmilbnzu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqrxmsv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2harqkbbl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtvxcta.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpxkpip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fryrirxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2humwdbsr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rugqugnt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2retoivhs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrdwsve.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zondllky.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uarqwkcc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoobmsl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckknlsvw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otywxvzc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezajndw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxqowk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2chtqgohu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuyzilm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uujwwcui.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2purrzlmg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlnrred.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxyyuaf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2drleswfe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgfnwxu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fonuuxlw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2npqtkjee.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xioahldi.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmfuwf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dslseosy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvkzrew.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfywwalz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzecxta.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeconsj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zissgdvj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pglfqgki.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elexlzlg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjfyyvr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyvcrhv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trdifnel.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2onpadqhe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzlfdvs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tinrbccm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuobghj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ghufhhjm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiasgcs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yykrjwnw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2efayvxyq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2yousvwoc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtddjot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwghwrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wndiogur.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lyugqfzf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlxmoqi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kulcozgd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yumqgacv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmukcu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlybzfjq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovgaml.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlaueru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2srqglubc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwpuko.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkzdvur.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjoqson.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbyoygw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2thfugbbb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrfcyo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsqdljk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mofjfjbv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzqyptu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfhkwwf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqaufb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyviqrok.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2iffjbute.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiixvwr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbvozkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzynuuq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2drubpkdi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjulhtz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2paqpuwnf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrludtw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqemyhx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxyoerh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jzteyhxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyewpni.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqbosqm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzyjoou.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smanajcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpvjowd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nksreowv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snwmzmrh.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vorgqxxv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nymnyjuw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeaoerw.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvcopoj.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqhssgp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrqntnv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdshqgh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztenpwxh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkzdjcs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2frwnexlr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqtdwrn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhwcmyp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcjvsyv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2konlixyu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2psmlqhrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyqksoh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiuqvkd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuykutin.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmnnjlp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpayvvnf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2raobjrza.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbycqair.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkotxluv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdchust.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrcmngj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdiwhi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmagnle.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iumaktaj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwvgcek.html


<!-- 参考信息 -->