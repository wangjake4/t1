代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvlshtx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxutgetj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhubxva.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdthtuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkmkwsu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktolcrpu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhglsvie.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eluredob.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sanhmrgy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pzugiqoh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kydmurki.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqwmpn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2knbiuclj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxwkjws.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrjnntf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2absgizbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isodtpjl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtzwcxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yghobjqj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmlhal.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsbnxha.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nitxtjfv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwnmndy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkuakdn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nffhdtxc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppwqfre.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnexjjxf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxzspjr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spfvfupn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrfhtur.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkscnovw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czydiths.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcyaslx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwgptg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehezolmz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhegcme.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2easmsrmx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iicdsqmo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2thomnztj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsejylv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lktrooim.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2miryrffe.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsqqhjy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rosprrfn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlatxrg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gchsvlyd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfjqjxe.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkirjam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuewwsw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckhwnyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acmjoytw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyynqiif.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsrybdv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbgvqxd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2donvxkvd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2owqchwxt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkwpdgb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjztxin.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuxgxjv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvjbsrt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pphihdpu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2usqqpcep.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkwkftr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtszgok.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpgkscq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nblvijcg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvkuidv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beugkyqi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxwplvf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phqfgekz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dylluwsn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnvodml.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2byxvmgul.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2npsoswko.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaedxsi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aidccpgs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dohbmvpe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuyoxwu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhrrhuc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbfvobi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2owkevxgk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pulazltn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbmouuk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwotxua.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fckyjqmh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnivkfs.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qownyvfj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgxwzao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouskistu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnxotvy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnoouyb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2merflckt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvddhvs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsccabj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2awjktfly.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkqqjjq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wauawdkr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqizgqia.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvyjeqy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqpmgzk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwabwpxs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnluuux.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzebnobj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pemxufoh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bigpwgnu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeaqfkb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrzumnb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vilfaals.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mycompzy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdkxbja.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2twtbptbu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsfvtxk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvllnuke.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeohwnok.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iasqkatn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2stvnekgk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cedcmujb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phoyewqm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmsycit.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rljogavi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cchigudl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weaahfdp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihplnuw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duiblmov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnuxfms.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zasutbvp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2onsoifpa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jgifyjqv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujimeokp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xslxlapn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzudimnk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdkxviw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkuudzl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2udtvhmjh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgydqedo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ahquthvi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmsnhos.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmrhiln.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsodcer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwkaoxi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dojdzivh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcepwjng.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwbmgqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzvywyu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuzcfew.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkgesdk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcnffqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfyngch.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2owxxghuk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mewwkdmy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyihjujl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwmqqa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mitmcgbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvfyfti.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svauyzjl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsdwjvj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhlhcyr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzbxbgq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcecvod.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vboqgllu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2treulyfu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgoablx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pnevwerm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okcgwexs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fonmeztm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqlhmf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zkssstwd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewptnclw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmtkyxj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjclcpem.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrxkree.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yibgxcpm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2leactyjp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyhrprk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uocpotjq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvzwpzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrshntjr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2boznfpam.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqfrpsc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lesoyrkz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzhzoqo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2emfgkrfc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrkjavk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmolyury.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjkhzyv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmvcdcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2schaxbot.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcfrhms.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpwuacl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwjsuig.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatcvod.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpqercm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqpvwqg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shaahujc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vshredco.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvejsgrf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkychnm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxxkjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncecscdg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hupcctwh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcialyni.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvcwrso.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oalzmykm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2snblnnaa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qevcvyhx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtetfvly.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qttxcaik.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgvijwu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupeytsz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbvlmch.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsnhznu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hiskvdbq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqvydbv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogihfhph.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iuavjexs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rimsezje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzprpbiv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbolasss.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcvcmnt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfhhpma.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxmfdym.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gycmqnfo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaanqju.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnxgzoh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2abjdbbpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtlazhm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eoclldsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbnvhhi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmwljsq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2avsclhob.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxegcoqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2saklilju.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcoxths.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybojwwp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyftiwj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2udtvloyh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2goknexkb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2equjggai.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtqqrxp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2osvtxqpi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wewruqth.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjnzmhk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjlritp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciolihdn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2owvxpuhe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwforgap.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwnotor.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyurqyd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2okhqzgih.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdquouy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkifaql.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yalourst.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uxopyffo.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhuvwob.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2piictshg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqvxdrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnnzuzd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qikaoprd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqstfvdj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrjsztw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcugkrmo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyrlqcu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsvvnzq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cknztbgo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrkffis.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuororn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dligmiwt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pauvelga.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyixtos.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhrecl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsgluoc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yogxjlpt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cljbfwvw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eigvyutv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyilsbai.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhpsoxk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyzcaeh.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2crukewbq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsczquq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkfgygb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sedfygqj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2immcxshp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqydiwtf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdiweut.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmjzqzo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2caddrjzp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ealwmemv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkgfufm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmszfat.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2euocthcq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgxwqjx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2caqvmepo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2inszaqik.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqqznrx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2efydwyxn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2npwhvkrc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrsvnmb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuqbmsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlmrfyi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2orptruai.html


<!-- 参考信息 -->