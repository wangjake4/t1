代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lslkdbhx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jsovgixy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prdirezz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsepkxos.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drdzeeup.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpddiei.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2psvbaiwr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkfliqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpurwwcs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbptsrtj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzolthx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfmlobv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoqhdod.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrqyfr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoeprbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyuynif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsskpqt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qblgpdda.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2koumvnpe.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ithidfia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2voerbjax.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oxajmtxd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jtodtqbw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2trqokfid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrnqqyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bvohjips.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvhildn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nfttvfmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asaxgsmh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2inqpggmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qohfnodt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzayms.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtohwnm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqnthkj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eozpzyfr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmqagh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxmzmcf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nughxqug.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wygfzgtq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otgszvaq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtaovpu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2icxmohru.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2havwfjgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxbwaqa.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rztyfcxt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsbslai.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfqyiu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2auhwesre.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsicwfq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ounbyplq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqbfsgu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaxyldl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwestdr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okmfkeqq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomisdrh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iyezgoal.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gebaqans.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdeddct.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhlcort.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfdsuiu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjqdcmv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuivyra.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqysemgp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtdwflj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uouqhgat.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drgyphmf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqyatmo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyvgoze.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbscdez.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adeykzmn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abvhojmu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvuvidu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flidlooz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxegftwb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatrcpz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqekebfr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkiwgqv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xppsakng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raykbnkn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdzyevg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrvurzg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjioczmn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqbqrbl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmgbafk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2daxamsik.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2szlzljkn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeemlso.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrddewt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmwedxn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmshdpso.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzdhoet.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2btwobobs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2myuwdjcn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvniof.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mrblfsds.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bckegsrj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maaqqdca.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imuvlblc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqaznch.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzwuwrx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlwfqnz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpyhco.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jijtwmri.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wewmhloa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzbbceo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhnqpoa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nmapiyim.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhwulzx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpctiwx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebkiuor.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbbtdik.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngzrrsq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ovffxjup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehejstxh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tllmyjsd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yisdwtaf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgmxuhq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2svouqhzv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yofuuwtn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gjipdpva.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrdsuyz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qidyoruy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tyouzdks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwwkjlw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envsrpbu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvykjrov.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsimmde.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yblqjcfx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcoreap.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoowmacw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxczrycc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgvjpbe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kttibdvz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbapray.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdeshbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iapbzqmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oausfjuh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osuuhvqs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2onvvrcyk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnelwhhs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jircxtan.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2igkcfkpi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmuucib.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbxrrtc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wyucbxqs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwbfuba.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttabuot.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdesfnj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdxykfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpoxrss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxsipqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtccdat.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2adrjacwd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qshhohne.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhuqnnf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2srybvcto.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxvykq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzaqjyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyixeot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xahugzjl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sljqsxab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcisnuu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxeszbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaavcey.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmxnjhk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpdkyft.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaqrrjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgoracd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qygczydw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdmujse.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2skiwsnoj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gacoydtx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzunxih.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvwemhn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmpyxis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhhzdvm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxpdtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niatekci.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ciimfzou.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjsyarg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfcwkxw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qejddjce.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdnsraw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rybpxfav.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcepaqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxmyerm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmmbkgk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2smqmmlat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwwuiny.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zscddrun.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfofjunv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pozvxexf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thfcpqdu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2iskwdxuw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rruwnrgz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmecshhn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yynzepxe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqoabwh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2czhmlzru.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbaibab.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uijskcjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxhlqfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlyaqya.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcaaiht.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqibeluk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdtbyfx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wxngjorj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuoarvl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzcompk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uayncgdm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qigottxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wediqtlx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxyhvs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzpmayr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvcroqk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnrndks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzwoaea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsirtyi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcznjar.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cosnlobd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2svuedrai.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uyomusmq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gndspblg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eitxdtuf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vivebcia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuzcsxt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmivcas.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xziauwbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwslzr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpyuqgg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhnmzbs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmyaybd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2glykresy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrjdlnx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeoyrcl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pedocdrh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvuzcem.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsmxvdw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjqakll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vstmjhga.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsvfakl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrmzlke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwisjvai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2anmjsnzj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2srjemziw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2htyckjhi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2budnlsev.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2epztxvpi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2knrpoypx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrggmgh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awzkrrsp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2alnufhjt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dguqagvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qayhrftz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjscjzl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwjljfk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdltdev.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyxtcpz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsxnoia.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaiiurg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwwfwze.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiduxnhm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2etcqspqw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tgivtvxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2avzoprov.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjebqzhj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvvkuwk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkipbjex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fktgpzzj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrnlkff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkogxvoe.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbhaawf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpijctv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2guuuewdv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbievtw.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmpvema.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2veoxthiw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuehteiu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2osivguhy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmvyojm.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeyxyyo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2miaimjfm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2javoattv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmssren.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmeqoit.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtodjnku.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpdpikv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvtcowi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcytiumg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqechwxn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthmcvod.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xdygswjw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2emalftls.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aetofeeo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpujkcz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2afvomhpo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfgpaa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppigud.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ephdaglo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkljuer.html


<!-- 参考信息 -->