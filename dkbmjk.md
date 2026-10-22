代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fknprnqy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkusjrbg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxzvrqf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hklmoyqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyhnllx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopkcel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slbanksx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oujpshxi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2owpldbyd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvarcsx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejysttju.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfpvjqf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjyawld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tteedxlk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbnmtk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrzeimc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2usdduljy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fjikioil.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2euyjmomq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2emjraxlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhlobdr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsamfco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqveqtn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmieikp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjaicgj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guhphqbh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdidrpu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnkafie.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2totzpzhg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxgtnnf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfxfuqc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuvngnu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fygfkhaw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbtaqwj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqzoavr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzagjaxp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgkowto.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmfucjc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrytkvna.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jufqnkza.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suiytywq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sycmzohx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgelsvx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2awikfaim.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twdihalr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfwnyqo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyomlzl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bsagtsjh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vynyvkhu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dceduzce.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dodwzhls.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nflkzilt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqvaeuc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridkvtdi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjiiqq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eitosyor.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2njetdpkl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfawlmt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxakuuf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhxiyvp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrrhqiz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shknmupl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbynlj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irxulflh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rporcpmx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xajnxnjm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vevyammq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqgqndl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2piypsyvq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgterpo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxciyxio.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpboexn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbsvxzf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsldmvl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrngfmk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucylvceo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwyuuel.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2unobrsvd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylekrur.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vogvpyid.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvibxxw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2igllchoh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcnzdmj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnekasht.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cksxfkcq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xebjmkum.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzoqnfy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqazdgn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvmfban.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adbfbwbx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jffeupzq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxkdvav.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jildxban.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbapzpqw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqcsdcu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzafxwb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kaenldla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oshnhhtq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoibscn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhwifed.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzjzcpl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrfhijm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcigkmqs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btpyiabh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wvileppj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2utwvcryw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iycgbdsw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2abpyvtqi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsftxkj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fivcmsmt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lodfenns.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaeyvrz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkhjbcf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2toaprpxq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrblyfi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmylhsmf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdkhpm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtcxqyg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnymnkua.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyrahfj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2utxnitnc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlbwqwa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvansmyn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2czxeapud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwgqffm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stosuajv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpsifcf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poplpsll.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqdizvj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuxyfms.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmvndty.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwshoyoa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqirlom.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2btxqsdzj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rymansik.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrqtlwh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2frtxrugl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qihexvwl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2opeduisb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2czlgbnao.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuoppii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbrizaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtkhzkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2niqxalir.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbpdegu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxivfhmb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczbfjka.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvsyqds.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawgtok.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yvasryha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cofimpma.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuruubn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2epbyojgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgnlzbn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuptbbpu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2irsmdcav.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsygfhg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikmktvw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pibtprns.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwftnkc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2krzpfmdb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdrylcx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lknnuhah.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iohjdddf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldkycq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrmiftq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2buujzqum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzezxuf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpwovxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pphjkrfr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnlwstx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrxwqqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veifugcr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksjtajg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdqqywv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxdmtke.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2byppqrio.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srquwixy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwnhjmr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqeoogg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkekyyoy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwdlzys.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoqmslt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ergmdlpy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwikpcwp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvvjbjp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nshezmrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lonuwpmb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwvwlrf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcgpgke.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mafadaci.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwktxlxd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2otcrsbox.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtucstw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaizntc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wceixzoy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvjhwnr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxpmxdo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqoelvw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmwxvxt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmoeon.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkotfsli.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdgoxzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbckuvzl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqjkfsv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzycxeb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwaaega.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xluqsyyp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngouarwq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnfvjpr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaelidg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbwwgih.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvsjaf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2abeaybuu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjkyawq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbbxrn.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvfxlct.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwwqoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtxvpxr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ablukysg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uajatbnw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cztcmbpa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdkghdg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nffgligm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrrazqv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zltteisl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2svywyjbj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppidahkg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqihvxyl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qncgfrws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmqsqgc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xaimprwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwdvxro.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2etyoulbo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2efrffnhm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2obuutowu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqqxrfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwimftj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdmjkij.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjapxwt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhmigog.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2owekpfnb.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjrflky.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2skilzffz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnvgilv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgufqjkw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzhohvg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znuppslr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxvabyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2egsmcyol.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2snjsipkm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsubtli.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxjjhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuqleay.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxoikra.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2elzybunq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2crtpumep.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgjxiqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxzgzgm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2elxaimpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2miosghwo.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2saxyqrol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nspfgwny.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbujkcrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrzbizj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlipmlpz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgqkmbn.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdxwdge.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxolpwv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmefqsol.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfjxtfn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvxikxd.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2slngguts.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fswjyewv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcqlftg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcupkmsx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfplnui.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueicfbct.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngwidbc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpgareb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrajjitn.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmphrdd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jieyapus.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhfojzw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hyctqctn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aomlbtio.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmyskxm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2auljlzga.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqfiap.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2lveithjg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvasrqtb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoflpcne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnbymni.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpijxbz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqorejuf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfhsllv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpfurvl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bexlewkn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrbouhg.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mlscrvda.html


<!-- 参考信息 -->