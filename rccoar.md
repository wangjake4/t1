代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuvnomu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phqjzoqm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2minpuabg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjovkgre.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywcrsee.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vatezkvi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dypsnyrx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpybsbh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nkltbpen.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjmoidv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gruzrofo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkwjpus.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2updqcork.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjimogg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2imsneiot.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiueshy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynccxywy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfvkxaj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdhcpjw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpuhvbu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oayrsclt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfttwcm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcbhfgr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvmdyoo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvjbmms.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jddykeng.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huuadbts.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adcokhoq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwukhs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txfvhhaw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnkymcn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpoegqw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzvhrva.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajowtyjw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmgedod.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2poosxofw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dejuugtm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvtjpcz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgimbsv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxvjex.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvyaduv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2exmisfwn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2svgyhwdl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ednvolkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfobojc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjnggdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmvngh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ucndbvfr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkoqlb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dglcmrlv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srqdwyid.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndgyawe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpwawme.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfvbpmi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprpgst.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiphklys.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjajocib.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2scrthfaz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkaflhw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzizbwic.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnfehrg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2marhriyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2psfphlpc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqioqin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wndpkcsy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwqzhtr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtzopdj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbeyuhq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuihcpnl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqdpnjh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdavvpy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2csfallcw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzqecjq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rphryssv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjrnjq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwuwmq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmvrapa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izemecrp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqgmqot.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujihnvrx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiqtwwv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdmkogj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzausbh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rifiiqzb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2trgzpalj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qelsvwcn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skkbyvpg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cftqtxbp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpquhge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ralbumlh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtkieat.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuerwned.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzmucn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjvcpvn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbbphuc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkidlfq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inslrrbc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjqrhfg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gfylhwtl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueepdbko.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmiuyg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdbfymr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oioajtrk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbrlssc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtcfbal.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eegsyyqu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhfhwze.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbojlcr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2miqhpxqz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzobbyzf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2liuepegr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2obvkerkn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcfjgzj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fruebbgk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyqnuuh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brrkgsbf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfwpvqm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjqdvui.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dalebmcr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtewpwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dodlhdsq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atyffkyt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpzhem.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vajwwwga.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkowzab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrnldkn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfolfxh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvtbncb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2obfaeqvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzykqbzv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eyurplwv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcuanfa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvkiorl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjiewcl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoejmoy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dckyatfq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2aovfbykd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbcpmyu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqqiyve.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqcians.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvrqlaz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqrukbg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdialyvw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pewdszmi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqyyfmb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txrnnxnc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqkyrbk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzkrtfy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhydyar.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmojbgu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wstfmkge.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjppwmoi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzklziy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzfjjsh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txpfjdar.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnekqavl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jofvsipf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qixxuwph.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjffwvk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vcokrrpl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2alywpgwc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nbopsnug.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2askoprlb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jomumfdi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2weuxqzbe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqkayww.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpuvfiw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmemffn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvleskc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrefnpzi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbxyips.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbpwrp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvhagbn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsaqafg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ninawzqt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvtspgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmpmhrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpydslaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtnncny.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixsztp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uudwrtfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmousktp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdqmgyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wunxoeuv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwimoi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhdoknf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzrjxzi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmoudgl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnscmmc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2adycykna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugcaea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcjnixa.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixccnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjzfatv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtyvweg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2unjdxybr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyopbfju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkogsraw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyxhxrr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznzclyd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aklbshir.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lurkhsvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjldby.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzwrbhj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbouelc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqimavq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprezaqv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaepchf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aykyhdvq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ickdgxho.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrohsht.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlbzyda.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzxlsxi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2czlwtths.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzkeqgr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsqdvlt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjevoce.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfeazgh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2sejobtdl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwuxghk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzckzxdo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsubpij.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2spqmqoml.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiijcczi.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byfcdnqp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oonoietg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnnrhzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjevbsm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kovbnsui.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxvptp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qltubgjx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxebmkp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znagedcw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeuutjn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xatfogym.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqyuilj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqucoroj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2shykpsjx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2optvgmpe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxxuqfk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwaeuxb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwlywa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2scdqtegs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hgicxynx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbyyxge.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasdxuue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjolpagt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzeshhx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxsdgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzdolhs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kerqazzr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqzmiut.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtpuipg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsxasux.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoefihj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dznpievc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrviahu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcnxmx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqshakc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzvtfdb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxldsmo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpahkulw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tobxtpev.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgclezh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oumlnssm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vocwgmqz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zrffrsvx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxnrrax.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwhutja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gabynmok.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxdzjix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htszvxbz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmdogmw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsanxdoh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvbcpzf.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgipamr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2eczlesfw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2osyfnaxn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rftpxjog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlpdtvn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkwzipi.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2okscutam.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpddiahx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zggumbqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywcgsw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbycsfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgibaut.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbcanjr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gprsgvts.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvtbsav.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjxyisl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sneqsfhz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2inoxcrea.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxdfrqr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzholqv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwawht.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yngmslsh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwnuuct.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmirpwkr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdpfadh.html


<!-- 参考信息 -->