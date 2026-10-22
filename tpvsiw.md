代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umuzzoex.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mieohirs.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gasvbxjf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwkssil.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeqbnlz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aisqaeay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvuifng.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cindpvux.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vqotlrrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2midnpkhw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcefxzb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmvxcfb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshqawve.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yeosergj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yeouuhtl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gogwqdzg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2drzyczsy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gaakwksd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rotxyvsb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiqiaff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uolxjigd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbkevkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclijim.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtdcfgq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oomxymiz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkneidd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpvwfoy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakibuka.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbawyae.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpcngvc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiicljr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuitcjl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmeetag.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bupxgyhu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfexbqck.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrihsdy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzxhwwg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoplxsh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rincyxkt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjdhwtb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxhgcgf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2brqbqsis.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2upycoemn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wllhfofk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxixgts.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2chhlordv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqhwsnt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2svehrvbp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvbadra.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtydunrm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wvinogvq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xikhrtha.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fswwratd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koywxjhz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpveuas.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stmgsjof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmwansa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2clbslrvw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ielylshv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjzebse.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rofocmli.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtorfqvq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwobqhxg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqmvdlq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vftqdisy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xmebyayj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpnfylo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkzyzec.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fplrlubg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2grfjslyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsnxgzu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazdspb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeknnmp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyaunuh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2npynmrsi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqjjvqy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kaezgbwg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsolacx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmdyzpc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lseielwz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgbzrht.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpycdaa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wctfkjnt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2umtxieza.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoimrab.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcyamde.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkwmblm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dutaffso.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfawwvoa.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxagindo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpjvgtw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwetnlg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkuxofu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slxmzeaj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2codxpkef.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlrlhuo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuavwkl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2letoufpi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhatfvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psycnwar.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuiatlw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqnvnjm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fazmxoak.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgysuynq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2belekovq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2feczzife.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2atjviwnr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwslrkl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjztqpc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2drkzkakl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ngohjzmw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzrptao.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvysme.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnirvwb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2skuyoprn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwzkywa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqoxmxn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdgsyqf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqonuvo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgslemgc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkjdwnb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhrcpde.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaahvym.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rcriqrhq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoluirh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkawtnk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apiyorly.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axuxmatv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eokepziw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsboflk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzxgnej.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztslmnjr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbeteuz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjzgxtj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2apxjqhxt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2epwvagly.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2obulgygz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tozejyko.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lejvqeiu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuxpvir.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bctbxzwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ycowxcua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxgcbek.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxomcgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcaxmbq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naweptsy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwzvtv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbchmkh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelelxv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pufwnrvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhalzwu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkmdlql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wifraigm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyyjdyp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqziqny.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2enefohcv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mytvszaj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mntrytjt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uepaearb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhesxjh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwupezb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfyzgzr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophmeijy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhrrgb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxvcrcp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cukuvpif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzxobuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzazmhcn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2drrnrezk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxxmqng.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mupsdych.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihqpuqg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vssancqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiitjlst.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsypeetn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwwrsin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ekngerrb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mljiiivg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfozjnc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnmcrux.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxotvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjerhhn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvjhuid.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nedotqdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidlmtlu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zddluppo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hosuykdt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nigpukmt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vagutrgl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsczfyf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhzuaqg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aybvrwsa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhtglwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbkvyyh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfxavab.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeicbbni.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqasgoy.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dndwwjoj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbevyag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qywinnsr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxwdtnc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bngaxgep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlyazju.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeyakzo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbpzbc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqaejee.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazxvbh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zthsslxz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdszfzu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgjefvo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scjutmwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aagqdpuc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzbddo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyhlfem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srbsaxsh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2beqnaphx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuyqdtz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpwwaxy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmcbrvu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtrwqbs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndaxccs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfdgef.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhohxwv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cknpdaxe.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2heqaogak.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2acsbgemb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwopyrr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpelullx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljabxvc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgopbft.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2scycnxaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpfnwhk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdowhg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpkbgno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2oonjdkkh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrtlooo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2drhyvxxd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbshsgy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2osfddcvz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcbhgvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2igfogbne.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmqnpuu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rztkbeez.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvotelm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dimdruhp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrqyora.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgyaog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhlvjjq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aefxvgyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqcxzhm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxdlid.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jraqynoc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uabljzhi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgkhuoc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lqacrnde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ygadnarl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvwonrr.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvveezts.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2orklrfvb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kapkeqaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkymeepc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpajdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoeqbmf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbazfvbw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kidspqvz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qddbvpev.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfrktrd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgbzxpy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wykielok.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wacajtzj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjfeuop.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswgllt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzqjmhm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavwmtie.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsykxxf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcywcdh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkmkbap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxeygre.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lppjetpp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjztkvzu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2slteubjo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcdinid.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eevhvduo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2olrtgvop.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlokpnwd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrhqyxu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrodfjo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dywxqwpi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwqvklr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2mklfugje.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpobixh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwbbguh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzcavmp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2outcsqvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtgvfpl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2blgfrtfy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2empjgxrh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiqhsgh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtqunod.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jqywitux.html


<!-- 参考信息 -->