代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsufeel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tagczcok.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqcsgax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eaympdkw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2denkoymh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpldzhzm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bykoqzld.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obnfxoeg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlslkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxqkwo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnauvsi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fignlddt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtjiqti.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvzbyli.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlniaxw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfcqvkz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrefesvr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abjmrexk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsefkvea.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddarqcbu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2joupacni.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bppknrpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwguoi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuozxbj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgqyrpj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgoqkkl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkhemvp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2barzvala.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvhpewq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuxxofx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvsdgss.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gckxjkoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzzxszu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eepbdxib.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2levsjoav.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqyjooa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aismnads.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxmqbiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxudlsfv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbynrdoz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aeskpulk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhssxzot.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwveqesf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veexneiq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utibxavp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwdowy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arrwfkcq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zydocbri.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkobkdv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvebxkh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrrambh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyewojj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcbcpxv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxtnsep.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhosluw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mokhouyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikhlvzc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cukfrhpk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgakfgi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrsmgfk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jglyvgjv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2duztyqsu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgtlhlh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnikofh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjbdnj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgzhlrt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vlylwzml.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vngipbth.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeawaiit.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgycisqx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdyjchy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfmrtrl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyticnm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqspxsc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgoybrf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmypxit.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2podanmum.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vacmuwvu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iksyzrtc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgtajgt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqmnzdw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkprcfy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2doafzvfr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzkpjbp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaawikg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaslwyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mllliaue.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tstfpkra.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrkyhvm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkjyzhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2npwqfrvb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edrqktqi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2supesplq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlrdyjx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspmxsi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgygnkpk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvppkpf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnoqzhl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmxsjz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpzaxpz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2thasqlfz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urnmtrga.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ycctgeqc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvadfvq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfoviep.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrioffm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeouhad.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koeptras.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2syyhqvid.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elezrbup.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orluamgn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrvtop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrxprvs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upyicjar.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvdpcbu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkuobmk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciygdniy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmwjxzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzdqyn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpimdhe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpyokcv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrhpysw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2trmamvvf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fysumnlc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuhcydg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yusorynz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuqyczj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmaktfs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ronbgrnb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2snmctlxw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfrwatn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apwjborh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrwqdpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hriyqarh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclyoxpg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2odyytdpr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfdhefj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yohotzoj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqvcsfn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaiofbc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkavmvnl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhjvchp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lflnhpvk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2codrvbcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzxkald.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uozdmgch.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgyicmr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjavvgm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2maewnlsn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbxeitz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2csjsnrxo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kboznvzq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoaztxf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqqulla.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaykopo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zihlihxd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mttntzjf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsbyeqh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nvklujix.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmgvgvg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pftiswoi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhchvwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdqnyle.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyuzpib.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vohhnlns.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcwwrdd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tofklfwp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upiuvovp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kyprblnt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fseffwao.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffltmmyx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuunuss.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjzeytz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohsfjks.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopulsp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2otnzjszc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbguhra.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmneutta.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rafcfoty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyeckaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mxocxufw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ioglcxub.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oxskckid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhptfjha.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2acsxelmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqllevh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfmydwd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmizmceh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmcdrma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqstkfw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uznewadk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfvgcn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjljzes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpucigjl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnlbpdt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpxedtf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2prirupli.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfjwnxj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzzsgqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeacdnz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nguyrcxs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uitrvckj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igbmfubc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiihmvkz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2plixzzds.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtgnrpa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2djmqdoin.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzkyzx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzrxvnt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxplbiq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhnvfaf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2owhkqqtl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atwyruiq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owoobpzr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgliuou.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfixkxm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tizlwrkr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anyjwqjr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjoawdt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcagnlt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbmrape.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvnfpjb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnynac.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2enyjvewl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2siwhdyhh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiamqvp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbbvwtt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzkscs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xttmtdeg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmrdvqo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvlbxna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2saxfdndh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zuecnyuq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jewvwqai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnzhaem.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jissgfey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqbyvil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxutdbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sedhqkxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2udmjsogj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdvoblu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oavtsmag.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgsguay.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xejkvxla.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rphwwsws.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsckvxna.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cidohjkp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lgchdant.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkxszqd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2doevewhj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2odtasaog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2usubltzf.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2sxscrqnu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyccncz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2efvthvaw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2odzllfez.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcntmva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lykzxfcy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mqycikui.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uncyuqct.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2piuekgag.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxrsluy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dynycxqw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heahxkhw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yartynqv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2eisaavqx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hciduxwm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2czxaeyah.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkabqsan.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrebmvkt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2sozipokl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qobqdfgj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrrfrpm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzyjtpq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqnlpxf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itvysrdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmlfvpc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrsochh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbrmvzq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwwboof.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhhfgod.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpffebk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2heylhqjw.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2negirfra.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvadnio.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxlaiiz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmiahmn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2swyzgnli.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2opnzozwo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotydmeh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eovirfpz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxdtxzo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sholcuhb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfbbxiz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfxxrcr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozswgcck.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnvwxze.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2twhrelpe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjxvjcf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cigvyoqu.html


<!-- 参考信息 -->