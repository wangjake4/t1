代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzivcnku.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaiwwwi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbutgupn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzzvvaw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gapwuzuj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pindusrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aymuecvu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgawcnb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuxfgzu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzvbtpm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwmsvdp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwsmnvk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dmefahis.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2leajqtgl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiheiddg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2srzzndhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phdepakv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgngetq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlotlrco.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgkxvmy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kbidcwed.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epxhvuar.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkeiztg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqligj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zayqlezu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhesilqn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdosbqsq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmanxsl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwtnlve.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wachwtuu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fohxogcv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiblccs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfnyhph.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgdjmir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdgdmcx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycczdoid.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpytwhhq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytxzdf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qklespft.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcxkho.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgytmkyc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npnwkutd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcfopar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwoyiu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiyzgwg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiooprs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmizam.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aijuktif.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujwrnat.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqbuza.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfagdubm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noasxkdh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnbizk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvsuczd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvvvvjs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cknimnzh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvntgzx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmhyew.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axqegqso.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvrzszb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeizberx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uktepxio.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxhvrvs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jryetujy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xstzlaej.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qovyccyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdczvja.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvxibhx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovztppmz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyjwspz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kulkpqha.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kropfntz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkbjtik.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoccptx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqptvilh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzsqvgn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2elbnoqtd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fztfrpst.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2czjvpqmr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gddbgkat.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2apvalukq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bheshprp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dxljwjaf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgznfht.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkhjnwf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzmllpn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2womvdimm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaqizxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pycqegjv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htjghdrl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhyayom.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rqifnsln.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyxkeqv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rntwodlp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqrysrm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdepjriy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvsxewz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrrmyhq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpiqixr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgwxzdp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sghfvfom.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2weeqgkle.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoahgmu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kgltnekq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2thqfxqio.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pbckdnhr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2phwcrque.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyzmffd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbwdoml.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqmpzys.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bggtseje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnkikol.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feermcyr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moqsgmgs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcsribd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmzfoue.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkuwtgu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmxqiym.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbqcfvz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yurhepjf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlhikzs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpcakyz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqchxma.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnkwmgx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoekbrl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgwjur.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwewcpyz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqdbauw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpruqzom.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jysqfvhk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rajyttun.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkuycib.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2svizybzj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hzahaimx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjwdjfs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxecoid.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2puihlfbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqgvwtd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jwubbiuc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsoeroq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmxylep.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqsfob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2punhucvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlyrilp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2daqggtkh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fncrgjam.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhflgps.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwfdhgz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxwsxmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpuyrtt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvikfipg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbgcsft.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqulssg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzwyewv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2luwmmfqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2atlvkmev.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngawwiaj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksewbicm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ublynfkc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrlgrpj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2awqnzckf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2noshqktv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxtsczg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dytdsgjd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lohblypu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwprtziv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbslpgv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvtfjx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqodfibx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2waweqyxh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwtaqia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonoene.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqrwdgf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkmrksl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvvdgob.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwetarf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjihztw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfduxudy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hanchcpq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjzvymq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijjgvdj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnxqida.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmgtibk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bximjhqx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tadwttfb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrnqbnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hirmrjvr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsgjakv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbpiavf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nptcbxfh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfvaba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzekoel.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjkprcp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvepzme.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzeldg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaapcnvx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgmqojo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydndkrzl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsffkei.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wauzxoym.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjfomae.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnaqcx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxgtmqn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2logpzgvr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwugbtph.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrbopun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bevggthr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmzchmc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qszrdibt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2aacyfbrl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrnotgn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmjswrz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xyalzeay.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjetizok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdjrnw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hxheobuc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqlwzev.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2buaftkgo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjzkvzf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgmjprx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyrdexx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2prebmhdz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2loxpgkkl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfgeqiv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndpiiik.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhqtocp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmfmtxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrqqsgz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpjdzhs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjfovmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbwbrlv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2poxtjomn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2telbnwfx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyqhvbu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2liybcxgr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyzitcy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrgwsfp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2odyvjomu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrqzhta.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxhxevo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqakxqxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbezlvjf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjfjxbv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpsfhig.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqrfjac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cskzorut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwrvxkq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2matyluzb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbbjzvu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzginkho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gjosohng.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrotall.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdychce.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiurlan.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2tswcatul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iusrshmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avjapacw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftohpdib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtiagan.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmhyoym.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzuudt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoreugs.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfleecqd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmjiyai.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ledrkdcn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucktfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmanzta.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qblvkczc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnytulzw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfrrfwy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ostqmmoj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtuyvja.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlizoaj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2clpmkfcj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkuzdqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfvsylp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkybepwb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ecixfehj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cusaryzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzliulrl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsebbjki.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtryqopj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxojury.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxwwqts.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxiuxms.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zworokja.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmswvjvz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uujwsirr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlpayrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2icvgangj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlfqjhk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcntgwzr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvhgdyv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxlhjzx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2opcvfdqd.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2icbxflwm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2paddornm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imdduwkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2azabfhil.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpngfix.html


<!-- 参考信息 -->