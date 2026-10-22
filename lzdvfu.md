代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahnctzs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxzkjs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvpwkax.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2amlnmaqb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsogmci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkfaga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnbwrmb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hunimkwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bemrcrwp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqvywhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzllzcg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2abmihcxo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfghixo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbjmyze.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrvrxyq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvahfte.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgddkobn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktswgrhr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbomcqbo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lorbattv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvwqyrh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2obybaxai.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhbgpm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuwlkgr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfauokla.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyjqnjg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2grqcuqvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwigexkd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diykynto.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzkjiiz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxvxtob.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcahuwo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjnmlqq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsstnwo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkulpasl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcntnfp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsvetma.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mplxcvue.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjxqbu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xijtofas.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmjxmwz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxmpnba.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfezmiiu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cylmktun.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyajbpq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtujupxm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2adnezlzq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qmahgpkj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuxwoqn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyqauep.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scthqnah.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cadchwiz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paxiuqtw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoatqtt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qobfhnoj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwltnsp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjfusbg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxwhomr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllgihka.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieinknop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odjmxksr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxbafq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zetulpre.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhfoayl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2khdsdqcx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgkpgkm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkleauu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwqlqgy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfotncro.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhaqcwq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2krshmlnp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubidleei.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2issmyfbf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vaizwtbr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvceuyaz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tdejddpq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uutpxhje.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cixmmelv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkuyodx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvcgmtt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvvhxhj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgglnhk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvonvbc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmngtuqs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2equcmfic.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnxyuvg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzfekf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrmqjmn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djkrhyrp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehttfjzr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxycuhnx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaciqcf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdpxmpu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqwuwrd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmrqoj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kausgdvu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vfailxiz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tmudckmk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vcibtexe.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmugagj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvriop.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyulyjo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tvffbjin.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flotszyr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2docbuuup.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaaetyb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggetywoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvwtmoq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtxwmuc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdmqdkw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2unubrzia.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbuklca.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoupybg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlxqkcl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iovrbxko.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tydeftqe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2laqdeaxq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcuvukb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvzqyoo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwczphrn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xheyilcu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2noxwyrbq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rczutflw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owpwhqqy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmyeyug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2undbvwkn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2arhkfqbb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqrnhcu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlyqszi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zxziuxya.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gfezaygx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wygktrfa.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2thwxrlug.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmqvowm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwuasjn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaxqvjk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2owllsmqd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nbplwfda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jajijvlj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efiufsoj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzpyplg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfcdpnd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubmdawl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfztgyvh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pshyaegb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mujkctty.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeuxswp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2byzyfinq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2odrlmtrg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwapfxoi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixecehpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2brgbsalg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2okefovxm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sythyvtn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgwwjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woufzmjb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfuvsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yymttykd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tvygawai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacpjzw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvjqerx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljewoxs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsoleqj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophsfaec.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lipbksrs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2linsokwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcbsxqb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eykinozh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtqnxiq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcbjrpe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrrhyoe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwxwhtk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izohhxvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ctonnvns.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwljqjxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wartugnj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqxfhdu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2agphlodm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yednrurn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2skpuvmhy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjnjayx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhocfngt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzunggvm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zobvwedj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhcgmxl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awsbgwjb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2exjhwzwj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxriiki.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovfglh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpruvgur.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnjbznb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdchjebt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abgnqzkt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reiwcpof.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jppreplv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cxayulhl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pspidazo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeviugi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiftwwl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzkpxss.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgermaky.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgffgzv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgldifg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2odnrhpkf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ancqljyy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbdzqdc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qmipjara.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kblymwxj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdaeehm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnhzqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otglwpoi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wxafdvma.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwbvsmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fahnpqmo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhavtjim.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyzmaiw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkacblwm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2aplknltn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpedepbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wictmhiz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2koucbcvh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcnvnfa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2paczegcp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqfrtvd.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtfplqq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljmwbin.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2crvqsrft.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2yujaizvq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2buojnbqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoqommv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkldnb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sknlyiyn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfncwfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiycsakh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfypbasz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbljaxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bclixuuc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2maqbkeil.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2crnjvztk.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjijvfh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzxmbvv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjvvwri.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfgoidq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbnkbqd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2wptrdyyn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2kldkfgku.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmezerr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtgcisu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcgksyh.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrugyqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmlegqq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2meqmhgwm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhumqtel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cellvdcf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidmyolr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtubjna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkmophl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxaecfg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ognyfbeg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlubnwks.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axduqffo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqvjevj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwlrkiy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdvqfg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tndneken.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvayddx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2risjmpdr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2baerlqny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlokeaj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hobakumr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyvyuot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvemtbp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2klcnozzf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeuipla.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcunbgg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jqytlclm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oietpxzn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbtritm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdichwvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgmzfbd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdlfpxd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzoexsm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2equzdcca.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmppurmu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuizucg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnzqjvi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqdykrg.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqgqbgq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjyhxl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqffpksr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqukikrb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnyvgr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjlpuoe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqovbvnz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjyqrba.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiquchs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2mijjqxtf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qisrwbve.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jldlbiss.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsgjksa.html


<!-- 参考信息 -->