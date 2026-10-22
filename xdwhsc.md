代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaomyzm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scklzvwm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aveyqtnz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbmkbps.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxglycd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdvehde.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpitea.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlbkcdz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2swftvbnz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qqporeep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rrquvirj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jvinfrrx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2diugrqyx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyzwyuz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoitsjf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jvejuetw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkzygdd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dnojmhob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqkdnkc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyowyde.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sdennlny.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bypgxuag.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eknmeure.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uowsjnny.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpyvrgx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgidckwi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcyltzy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoezdnhy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwnpqlt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iuohmany.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqzzwsx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zttriwtb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jisaphlq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzyhnco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xreqnfgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmusakvu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcruluv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfuasko.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxebvkna.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wskoxkbe.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvpbfcu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrdwfqu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhdycl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2schnjgkv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcrkwfo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2joevvdiq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuifcbw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwddiwt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlevrwe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrrtcz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbjjsdf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anhiwman.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprnlfbh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2behxdaha.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfgjlaw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cixyhayk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hplulaoh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsksrkx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wayohvpv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvvuopg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlttyyi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjyqykd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoyiluj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqmwuay.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmvgxgk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dchrhzmt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdktgnp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzygrbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbvyalm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnhhppp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cypwcujd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edjwnivj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkaonxf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lsikcosb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnaqfjk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvziqngy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsvvene.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiiynza.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2myrgdian.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynjczq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2afnccizb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhqwngv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pogajxyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvehmcy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xycpwmgp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvautbht.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kewqqrss.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kknyevkm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrbfuco.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2maflrlcz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vaewtpqy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcemaqq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqtlimt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcgbsla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2teruoqfv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snudmhzf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfggjzl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cggwkdca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oatdjuic.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxyvwwi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnedfef.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2reocrpgw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfkvnxb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdjflqn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jturltgd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ctncvbhw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zxggvpgd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yayctewc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zhimdkfr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xawhlgxc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjvgiqa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hodlgnvp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsyscft.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzebmum.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqespox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbuvrgd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2itckxche.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpqerro.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yilqiukg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqcnrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwaecm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmzytvu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxmwzdt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwazoao.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcyzvyh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcbamez.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjmbppi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixijbibj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrdrnpj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfsxhco.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgimkal.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2edznsikz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcadrzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cndeayvx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2velukldz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ceynlxam.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvqqpxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdvccrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfcvuxv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnfqqse.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkyvhce.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzblgydk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbemqfmn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfzslxb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkmlxqu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxyscn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfcjlxr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxjmcye.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wftjbxoy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zibmvhis.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlchntnz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfswsqio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2coazlofb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfswrcw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvhrdno.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnucwve.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2njrkeyvz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2agqqbdis.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxrsvnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzaalpv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjlrisw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpksnwp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbukmev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mriboknq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjgooy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvggiok.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2aonnugmq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnbgnp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzqtjcb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaesfury.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmbbjdq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsjaqy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itcieisg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcyvjws.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslkqeq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffnchj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzawosv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxjabwu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jklvehqc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrelahm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkzmyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvueofd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqifjvwb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ferkfkfw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eydqbfsp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2njiplfis.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygupxxee.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vicvopcu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpthswiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qegqmzzl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnhnrse.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqocnztm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvlijux.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnydpm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjuftgf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfhcdth.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruslgncc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrhkds.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymywuvbq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnrmwxz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgjawd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqzmlyq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwquqid.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ziozrzne.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krdjhbsq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftovybjn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqhdpoe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhiksns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncszlbnz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgnldoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbooyie.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyreqxz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bacikafe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uihzlhnt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2altmjadr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwzvcjg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtpvjtb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqkktfw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlouevk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdjsnjt.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcipvjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfubsb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrvoagn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbquade.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvwlftk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rldafslp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2penziopj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtydeas.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhfkkjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oepepyxb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiucwnei.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pidasyfe.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qflkczki.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsatibh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmehqwxy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnhqxcv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhfsdtk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uifypfkp.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfgfsoo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2yysktewh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywxjdax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtwftmk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyatbarq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzdfieb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhbwql.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpzprgm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmpgwwn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrjsklz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuthdrm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2svikbhrh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmxvik.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zuosqjuz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2buksinpg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dshpqivy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukixvnqf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbxejy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyyxgft.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwalxwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edparris.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rprooqor.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnsupah.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhjivyb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcofsne.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgokbgw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkzikdf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmrtuf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvncdofr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwsrljj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhbavht.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evgxnbhj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2njdbqwit.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xknymvrw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwdwhth.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lviceytt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxvhrko.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozazawnw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lforcour.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2deazolfo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwkquin.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jolawqob.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrzlcmc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcyzayw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxxzpai.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jajeiell.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mivpbosi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbestx.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyrjllz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mowtrtll.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxkjpch.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2npvmwdjz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbbjmwg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2arnukjae.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vepoccnq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdezklt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ladiaqwm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgvowu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2akztzcss.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2poifevse.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcxrxzc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwqccue.html


<!-- 参考信息 -->