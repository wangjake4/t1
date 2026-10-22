代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmgogac.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhdxkmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unasehvo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qikrvbcc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnowdalf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lygqiqcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2clcxsuul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmuaolb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsubksck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2benlaxhw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyndidr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgpkszt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2octjdpey.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrmbapu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwjtfzp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyjnmwd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbopnry.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiyuury.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrvmzjj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dspbglzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooosancz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbzvrdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pugegisl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sepanlrz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzgyhcj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2czhrfpjc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zygtilrw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmduhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfovvlob.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbyizfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpdydud.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rybzjanp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sisijltg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynrmae.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwqjrak.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejlpehu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2givzjygi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqyvjfy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsrnuml.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmpexle.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npkgbywm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqfeobr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asvehnnh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsfdrrj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkzasmb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvcgtpy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxqekvd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dboyagqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrhbshe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuwekyn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejphhvnd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nakppuub.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqwyxjz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlpuaur.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxonhef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nggwterd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrczwjm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfogsfyd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmuiqj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pegiotka.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jifwgmve.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reepmqlj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujgfdhr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmovqqt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yufndvxm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyoqnlt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvrczhn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaeecbt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgjwkvi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eevwzdzq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prvdujwu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uixyxium.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hohlrdzx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wimypbxc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oracgumy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2badgbcck.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cukrlbpn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhjcejh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agxwtszl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfytffz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfmrovr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kchhlror.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrkzcif.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gybeejcj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdxzbbw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrfxkfb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqxaydj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjotmwrf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mseccaei.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2awfdrzow.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qogwicuf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpvhmc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwsovre.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2chareqeu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hygcvwjq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2opuapwcy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnozeszw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmbkpyk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtwigsp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfeousf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvlxqgr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oarwkzty.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwkmkx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuiddju.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2huyfgsfw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvwcuxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2imodjxjb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrqdtt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrohzmd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsadacbq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nysbzsip.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnvemsp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsqyjlj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbcypfv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zifikwsl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ersgqiob.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdgklw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxlhyat.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyhsati.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2piysonyq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrinkpz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fglgzfkp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2apyrcxtg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpkczdu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoufagta.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzxzfhv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxuqdgh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfrzbsz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjskezu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhtvofx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2torozhjo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoufhws.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmredfe.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnydibw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vntcehyi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geesmzpu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwcsvmz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcugfky.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2piqwevkn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xsalkmlt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiymxpp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjnjach.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2alhlbflm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fenjkvoe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmuzzox.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlcabgl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvasoii.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkxnikc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdcywyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpphnob.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tobafwaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2drennrjx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcpcaxu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytukmfwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2behrjmyz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oaysfpea.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuanlja.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbzbvwp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhmtqju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdqiyaj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ummrqrda.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiovppkh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nygobqav.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfbrens.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hphoqley.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyjmxfp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2duthursl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sggevbcs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqlwmir.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdihvas.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwodsxf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2whjhdgqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmmubvm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngwstn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aajwvecc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoxxaxu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2citqmros.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgyvprh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xqipidag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzbdirb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsavafvv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxhefmg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfozkbrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrhnyol.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2epcyypzn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vanxomyc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gduspwgu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaabqnt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaexoxon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsrraee.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kecfzemm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcztdfai.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrrwluj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2niqqatch.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fafrugzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kliibbjj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrzcjby.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cazsaxof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvafvbl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrbngki.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpsegnz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zneurfan.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmjuszb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqxkshk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaxwmhl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjaploe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vapuegnt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvbklew.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqwoakw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyfzcml.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceygwwdj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpfujca.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmfjznu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoedmcgf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkhikqh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoxceur.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvkiko.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsmduqx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnuotxu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfuxmfx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2efnwuyit.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2siyqohez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jllftmcj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xuonihmn.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2loiymfez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftksnej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvbsamc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrlskjj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxpgqy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcqtdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obacbqsx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgjrqhd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhartay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2othyantj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jllrsomz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfkrrry.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eygweqtf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolmcel.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2buvektus.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzsvbw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxskkxs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bdatsuhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqickxb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fshshozl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpzgvnz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfjhgxw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcqhrzi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2aigniods.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2grlpaaku.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2djyvaekd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrfvtqq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2otdfzxsa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrctay.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2oepovkrv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvasryk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbgtjng.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlrign.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhthayxg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kdztibky.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqjtigg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtmswok.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfgwdmk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qfynooth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tyggfblc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnmmowl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhperjd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskgahov.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzifnage.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgpubbk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaqrmaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dctjigvx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjkosac.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqedlzn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjznpdf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugsjtlg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhadkrvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuorvpga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfakyng.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcbffjq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwtldqs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwebvush.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2biahlbcq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2muszclkl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rugzocaa.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwdoulj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oycifesz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqkbgwq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjdusa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfibzyy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxrrrua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yghftuxu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoriswq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2leujevqc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2unrzyofq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnjeqoi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfcttbx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2arlaopjw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2mtofscnr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgduclu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfncocgz.html


<!-- 参考信息 -->