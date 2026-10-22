代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jclxtath.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysysixnb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxadpiva.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgztpjeu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkjhjxz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvdltxr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqvjebr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzbjfjf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnnuqiv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzlwsza.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sisxnzqg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwotegtv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehnuuwh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mxitavtn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kqojcozv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqvjvae.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2amwgyilx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbvtvgb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfcyqra.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwyefld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcilwbc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tmacbpjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abfdvlst.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjbwlit.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlpwkmc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wggkeisv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuowhnvj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apzbvorj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sizyddhs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzklxqyg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpygaeiz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orycwscq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjybzubk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvekcbr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhhhak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxbbcnz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwsfcmj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaspxdh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcabosj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abhltiiq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnakiohf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxxgswm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oskphizw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpovnpc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2duzkgfqn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkhgyaw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmmrymk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpavzou.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysotouth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpktktb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydibdmqc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjmsfqg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtxfmkw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzdibio.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbazhjh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsebqnvm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqrtjhg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbctkjym.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsdlkle.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2novrggfj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hakpoyae.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzdfdgc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skbqybwi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvqlota.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbohxli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2guqafkmt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xftozjlp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btrlbdyl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mxssgtbv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uttfdcik.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfrelir.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozktwjuz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnsurhn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oowrfwar.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2slucdecp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npednbey.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvwckil.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnjbbpk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2srdvulrs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aacemdjp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oewabqjc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfqwrqk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2logelbhj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfjirqc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lsveapkm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2njbcbyaj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hkafacca.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqpbuvz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyqjwzw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuamjcwj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2worpwqzw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joajheyp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iygquknw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uezsvvrc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dscyvpzl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dljgjqle.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kispttsf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whwqpheb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmdlct.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdglmqqd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odycezjf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfochocd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acugbyld.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpopwfp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfrtqsg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rntsirhh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lpycedqh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxhwttr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cyumvakm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jlovwbiv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvdpsbb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2offustps.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xybbtiqf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiwjlcc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmxgnoo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonpdopd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvranbz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xguwouea.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqbogbx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuhenlz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohwupn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnezutca.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrbjcri.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sitrcdmd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfxiprw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhrszxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itqxpgmt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhrupbr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnboulwo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmvsgnl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsqvrfc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgymigs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyciqyle.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jldtkfci.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2efgfpjaa.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owegfrbi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmcksa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drfmyjxn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytkzbgt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sybqyksv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfzrjcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzorcvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnaefus.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvohhuw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwqwsqc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byqlfrqp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aljwbtcj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hrllqcxm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2stxlpntw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqfyojf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjuhdwh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwbxzet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvbbgi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkrydjn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oughpznb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuwqfnd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tttflbwt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmagjtjz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsdsrdd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlorkeq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlvuujd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtshfcqi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxydasa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2inozynau.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2srnsmyct.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdirgko.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2srxhjerv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijczjbvu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrslyra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhroxjz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kztistmg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgklrtxk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euzjprbq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfdiukp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acfuisot.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrxwgtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzwgxkc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxwslp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwtqimk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtgpijp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiwiokb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfwlgxt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcizrzeb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhcewsi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawbgqen.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptypyhiv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpczpyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bymkchmq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ikowyctf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbmymrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2irkgufem.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvrdwed.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxhncvt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qedbpqmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzgcvl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyanyyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mplxsrrb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aajxlbub.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hytwhond.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpwesfq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsvxggh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hndhdift.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpuwfcr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2enwkmpdp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ktogkpmu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sumyuhhb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgytjtja.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuazplu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uddrkain.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbfzsni.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqszjqfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njzfkngl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpehqir.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxxnoqq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdthptsa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyhkuoe.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkwjkhl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqorfmog.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sesqlhae.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvvceu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgimkiov.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoasvoz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xquwktjp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfkwtdr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eklamglk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdspmql.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpxipza.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxxpyzm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2krqowqmv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxavrayi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wivlfdum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tbodyakq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyipihl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzogzne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjinxvpj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2esapofkc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dijyizts.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qymjdapa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2gduzuiqg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzxqctt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kkautzee.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hkteleod.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjhohbm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gyikaamv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2baoovruy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbulssb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvdrufq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emdkxhnv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2crctgqgk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasctjll.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2btwyempc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyliswv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnyeof.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yehhlnyf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxywleu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ndydqgul.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjrngoe.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2aekfpuhw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjovfpew.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2teqohzee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frlocpfp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2whdtmlrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lazpxfyz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbpvcjv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oujevrsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2przopewe.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jndbnael.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikswqpzp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwxgnro.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmqjlmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnbhwyr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnmhvzs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoegqky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmakfwzg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sbttoamx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhepjxc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxjzotm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxblylz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnbgxbp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhwtfrv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrurgnqu.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ooplfeit.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbgozd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeshptt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqjqmmv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpogpbx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrywiodw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2tbanlrvw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2trxujoij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2obfjgmgz.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkjuxb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrssikkk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkhodav.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkukeaqv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2olaheutq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eotyvqhf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2epezyftr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kybxxqsk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvniseek.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dhixitzs.html


<!-- 参考信息 -->