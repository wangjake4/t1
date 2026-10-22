代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2grzdlrqc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdphgbg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwjgfrp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzblihd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlyfyut.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnqlmmf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zjulzxzy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cewmftwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eiufaitq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2redgrxzp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2trunyunh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vffaoqmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcncwob.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2afhwcmtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuyrucy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmatiks.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxpdlwm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egndmucv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhjsoyx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhgelbp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aysfwdmq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvoombc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyyhqpv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyqhakp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iibgwnvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvfgglx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjebajlt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzgvde.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emylvzgj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukidzck.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgkpquv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgogikb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enipfxdm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mvniotnn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcoyjgh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmskjile.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgtjtbs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgxemoz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhzexnq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2clcntaeu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2chwwrfjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxzbxkw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tekhgtfc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmfzemy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndocquhv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blqgsfzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfdaun.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esaejsyu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcjygcd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xphprepj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgyafsr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoelrpo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwdzgrl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmpqllx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcfgdoq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mklgghpn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcmocnj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emzrgxhw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abfgsbpc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqpbqpr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2maczvuma.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwqglkf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwjtgvu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqtikgc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuwfltf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjtyunb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmigfnct.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzkbieg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmonvkom.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fjivmqpn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtorebur.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjopnrei.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgmuqdf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwsdmha.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mawascpj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2osxbokqr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvfmebl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuvlhuf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhjdrmu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2latlldbk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhrusxx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvcpium.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgwemry.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkvpvqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfzsmcm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnzotsy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxuplvl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2avxmhrvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dgojapex.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwoardr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2edfdmbgk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhvquss.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xitpwrla.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guyaonle.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtjkwbb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaswwkm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjcylm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvyhetz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdunkwp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrutlrp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2geytmsvu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kroawkmh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhzovk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzrpjvb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdluftg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zisfbeql.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dstqmnbg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swretwib.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwcdkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdzubzd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inzviajz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkxittu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sctwrqvw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjpvers.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afettkuz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wfflihrs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlofmtn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsujkrqs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyippbcd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzrwiyh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtutdqed.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmyejap.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeykhdcu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmesmqds.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqzhfa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtlsnh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhsymhx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvlxucv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pakcsycd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmakgrg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2svgsyuda.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kvewfsrs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jxotxxcj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbaujyz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ieocqmbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlujkgoj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuociyk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyxslrd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ircznato.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyrbzbs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsanvrbx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mynisrjm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2edilzvms.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxudyrgk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmflgzw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evrwgpmg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffspakhs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yupxgfbh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnlmels.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxioen.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrcwht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhqrdvv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2psoarikj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2elaqwbww.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgenssf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntniffin.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeidbpg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsjrfly.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nomorxbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeavjuu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbshwsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ourcoscp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tcffhnqw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rccyguiv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2symyjswt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaauxfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxkzibh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmowtjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrsbeje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blqvmgtz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fepvticf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wknvzpub.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2umrozxuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fifzbrcn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xebccctk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwdzami.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwwzvuc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkkvixk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyabaxf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwkpmsw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zksrwrtl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnnnjfl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqaohdd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2odalxchb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nscofbza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kslkoubs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqtjixe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtmgkdk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvskzyqi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrefpa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tylparly.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxayqlti.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxhekgg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chaxeblf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjefwlr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkxzvjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unynclxg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnzohc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owzgjkrc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2leyrsnyw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqxrqu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxgpxbj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuqrfsv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twtiwctn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcxzmjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkszvai.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scgyfaal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ockvqyfc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlzrnvb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yivxehfq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2amdaausd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkquiis.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kguntrgs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwqwwfj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjlbed.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fuswwujd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tcllyofk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrccwfhi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrfdwmc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oasswrvv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxoxeaa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyuszas.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2asvhvomq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmabjuo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxdhdtt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2opiiwfiv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaktvnni.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2towhxkyk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mlowzmyl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2macfvgqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpopeoz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyedbgio.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uguizlau.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwijzaz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlypadp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrfbeul.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxkrfnx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmutyrt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxptcbwy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbqqyev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqtvik.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyddcgp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fditwhka.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaazafj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vokrfegp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoyvnwl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzrplzx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2quvccgoz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2empstcyc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnizasuv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiqzfux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqwjtbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njtslrcu.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtallmvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtyntbm.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfnhlj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolcczgj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcftbxi.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuphoyi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvzbwut.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wniyousm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bipoutih.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwnlaxx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsbkhlg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhbqae.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebexzup.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcsquwa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hiccmbmz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdufwlzi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsamgvs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvslectx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjosspur.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyulyqyl.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2anjzauou.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbogpmw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrdxgle.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uemwlfgf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bsywflgf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqmqiww.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2japnctlr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ianeljap.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmhpqgc.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wspubyza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpjkruy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2juyadamw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uflakhho.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xszmbjku.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiwwodd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcurwbj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uapfcjbs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqkljku.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hdggrimq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrupnth.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvsxgsi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmpaieb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gefgwycj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2umniuzqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjhoxqg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpbvgwk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpkvxtl.html


<!-- 参考信息 -->