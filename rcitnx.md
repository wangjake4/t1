代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypddnbmv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yajinwhs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkflibsm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2swakzbhi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvpmfpf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwyotsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrzgjee.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqunwap.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsjzuvn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzrvzu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfjthsm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnahdr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfzxsnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tifvrpaj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfjhmvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgyfnma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlqrohx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqrtvdi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obuviwjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqbvsmj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2werjsvye.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywudrhtn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igqsowov.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xqounhbi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vrictwby.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxesmbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2evbwpqbo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiwvjhi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjjjvdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvezrxas.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcaiwtq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxscorpp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkfudil.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngceggss.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2voywyyyp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwptcgyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyuutgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2beszsuyl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrmnjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woujrgmt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjkswkh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgengoj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tetigisd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxjjqb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yprluycy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeshwihu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzhqhbv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvsaof.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnndvbr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2psmzgcuh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwwgyjs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ofepyuat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkbadkv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjbqeaq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcurignv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrfmfhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvenff.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfrapn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkdyksy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ypebyjma.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2whjzclop.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqmaphr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaewhqm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klxoqlye.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncevykyl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxkhqjf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buasjicr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odfsxrnj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whwepmmj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwijsxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwdzutc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzclxlbi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urxnrynf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpiqofh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zulvngow.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gauhmlny.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnwcxde.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vktsrruf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvvarmp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgungza.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnxndew.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkzhwja.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bobgubyb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqruixe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcrkapa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcidnnm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vgynwrmb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idscvgob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukuprkb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dumqxprz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2filpyzpc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aooebdfa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffpugse.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwwhyzr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqwysxz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbgerbf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxwhkqc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liqfpjrl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdbwniv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zicdtntk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nidpkhpk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwldlrf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtvgwmf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvruazd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2owlauril.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdvphzl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzocjrqa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlfkogs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvccfefq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ascnpdwd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqpakzl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzttqrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbyqqjw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgeefsw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsedzjfq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaeoris.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiggadn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wldhklhd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2emkfffmd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2egvqvcjp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjbncro.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmswveed.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2onmqqhpb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2etiyugkg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scmexwrw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtnnufe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkvlkon.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyzexeh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnbkwcp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agimvocy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqepjna.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwcruqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfdnnda.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prkujjqo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwfmtxr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozsqjwd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaozjrbz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdyhiit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnlpvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpsvdhg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jcifghbr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxriejv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2imlgckcr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kvttaxua.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwugcos.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2djucsjbt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqmrkyw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwcotvy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ihycnxyn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzugtkz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dohmjcjx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjirzglc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqihtii.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybabbhvd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmbxsyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhwsoyq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yncmfwle.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmaycll.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wedhyhkn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqfjkxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlterrym.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2letogxxy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmhldlz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvuduyx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cykqsrgz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsdftuj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmjjwvf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgenmhfm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqsmkcv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdvbdh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkzomsd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyxfrzj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tnejjcga.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2igketadm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnowfnx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tnimgjjv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwqumet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjlbeyr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnwoof.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2djdsqemk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqdrxkv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grysjeog.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdeytsu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjeavqy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaehocnz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2izwamwty.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uebuegpi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmvtlrp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgwfang.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfxnnzh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrizcej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqncqzws.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2beriaqew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywacnkdm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eamuwxgr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvrvhxa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrnemtp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpxybvy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmnqjab.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsokxahx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdgjqql.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sdihlmfy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oppadwgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpduiwy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rsggnsur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fervyvlv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzkhghm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiboxfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txinzzdj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odsaqahy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylptowwb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlvwztu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzqmqws.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfndsarp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpigoio.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2salgkmni.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nepxcwwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcdbzpb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohdlcbt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfytslsc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tejckotl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2weokiguj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upwfcfkq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmqwdyl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwcnnrk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuumjrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkppxdgy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmznxkp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2miynvgsv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2juniotir.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqrozpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxuuqyq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sywxijrc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qruaxjxe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiqdjpz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfypqoil.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iijvvrmu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efohuagt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epmgwfaj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlwjjyw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnurijnh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuxivym.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpgoqqa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyfvkhb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjfatxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euktkvho.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpmbukk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyflqgz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2orabzudo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wunwtwfn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swlpopnz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdxmxod.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlaimrm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2codzrguc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjomqqo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiwdimu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhdqghk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pravdigw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pslwazys.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bqepmubw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmvlzkm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tatdkyuy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsccnbjv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xztbquzb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfpbhhk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujevqzaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lotoewso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vukxqqcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrdljtk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pudlogxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnchrrvd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtnxhtw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2podjijca.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjajfbl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkxuli.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpooyqek.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sqechfcw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bjklrxnl.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfgjaeu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwygkza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxfante.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxukryd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2atiehlcd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjycnkec.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfdohbg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlabyekj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjdneum.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmbzmbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxgltvj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbeypsr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kaostbli.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fdotxrcb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmcetip.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2iclxvvyu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrizvhj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xagggulk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkbmge.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjwndzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuqthum.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2atgvldbd.html


<!-- 参考信息 -->