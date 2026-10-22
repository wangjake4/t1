代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oicdqpnp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nplvbwht.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkafruv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfprllzo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvvdjal.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxlbwea.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phjpbsox.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whzltria.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfpyqzr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuypjwt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbzlpvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isqaigkl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2merreexq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veqleyfw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2luylltcb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2awyzxrzw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqsxpnj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2txibukou.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2krrxiwrr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkhxyen.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fwarbbiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zsihbxky.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dahillvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvrexdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlodzkkv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2judbqvht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpecpqfj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnuomof.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzkzlwe.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzukuuc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otdvvefx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhkhgxb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vskyraku.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2upquzwik.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dctiwuew.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwgbjxz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzkauis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ejziqisw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kziyzdtc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkgstxq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfzikxh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzshvfli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tonkxind.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2enevomxi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxslkpqj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxwcnme.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsxeadr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpajxom.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nptxhqdd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fajjijot.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyycppzj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uaniclbv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpfdvtr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kncgnkuu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cbguwnxz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqkxyvt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvngttje.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oylezfqe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taxjonry.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhrqvvw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbeiddn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjjapj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbtutxd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaiikln.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2urxiwxeq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfubukx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oexnfjwx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acqofggc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbhnqe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzmwzw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyabxuyy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqqbukt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cuostoqd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2frmimqcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axyfpfsq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazgzget.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiulfxhr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbbqsz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxxsswx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xykqazyj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbrcavk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2irxeipjj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvrhyyb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fipahlar.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjpdbqd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtwdndt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzlbjfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiwinue.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsrpndi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bikjlebu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbkytoy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwndqnj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axyohjpc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gofsqiac.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocysbfkt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxnabch.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpompar.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znjrzstr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zobmxwdx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfehkqvj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjwkdvl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvnonm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2miyuvgzt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qahxkyml.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2syqgvluu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhxgrua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eszifzye.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzlciix.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxygfech.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfarocy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgdskz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpiomqk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wipsclsl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwcomd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dwunlqbo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2imkrjofo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmftmjx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqcxwyn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrprjal.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcswxzmo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbucrkzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nchohcxc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqpaula.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hamjrbej.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfikbhoh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbijils.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkfmjnt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmkxlrf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmtdfnq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthgfmeo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djijqhuq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chxjcktl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnpbaj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxhcvxu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xokraulx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owhktukk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvgajg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfskepig.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iebyumrf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvrhcnt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfsffqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hmconssh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhoybhc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhentcw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfybrno.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtdhkti.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwllyns.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvcadwr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2evcdmckq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkpjmid.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyymtvru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2enkgylhm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2arhnkarn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exnsuoka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcptiba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hayegyzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvqqrf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqsiaq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokjupuq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2umwyhaqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yljvqxzs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjltsmy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iemystqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2isvkhgax.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqytqlpo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilorpmsu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2arxifycb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpokkwhy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yiizroxy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyvjebz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ekndlsth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjhbfpu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzzipxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvrwfdt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrgakao.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvppsuo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyfozlk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoduuvuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvqpjin.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avkdrjhv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wnepeagm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itlnbimd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyhghwk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrmyfuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2emjbxbsm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjlbhtz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jujqldhx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmesfmni.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyysdxz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2llbbxkze.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvatxpds.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfssfmom.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxdnmsb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnskyhzv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2braeczfr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqhitye.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2puuseixh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwfsdxp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2syunsott.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmaydyq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcavfzn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xeivdbdr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2owezeyht.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiifasd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjbnyur.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjxvax.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ludsnjqu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahojlcib.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khuijitp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wabyhdxn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lphrxgsr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2paljocfp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nslusncc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eirjzoub.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjrbopg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyynowa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrqskem.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkbvqmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnszkoj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtcjqw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcncyum.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iorgpvjb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpwttsd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ducngavj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkvgeob.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcznphy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbfrnyu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xvximlqu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwmcsjf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwocagb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjmuye.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsopwlcr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxkzaya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2edrqmodp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqrjbhs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaanpch.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfmwidi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzwuzbl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2snvslvli.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkegwwzz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiuckrh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcudgxu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzzcpmn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyasmne.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhtncdw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskemhu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mulpbogt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudmfzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqydgmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhupqzp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhudtht.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqawxdwq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnellyo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdwzdgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwrksou.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogrqph.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vopnndfn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpjacue.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2digqffaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qfybhbtm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nyojiulo.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnptmsyu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2caauwjik.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnbzmxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksziaaak.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olmxmqkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hakuaqft.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjqqylb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqunmszs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2twvivrxu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulyknyt.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptambps.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2eioczwem.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmaddzk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeqgfjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfzjsfc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irmmpekz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrhdst.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahynkpbj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhhwvkp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2klybezxx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvktohue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvncghxe.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwktlvx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyknlway.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqpdukw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edicuxmq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdutpzq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwljbeg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ityshsee.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiovgaet.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpzdnih.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlirqlke.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbqjjjn.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bomfhnzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eryirvco.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2etmeshxz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpzmsrl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqlwxfd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2otcanxwl.html


<!-- 参考信息 -->