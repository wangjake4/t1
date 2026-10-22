代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjddkbu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tulzbibc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmhgziw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cythqmxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrggovv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbkibtp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyuetrp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwnomvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwublvth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbijpiyn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rdetgjop.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wukbfbli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjksikt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbwrcvl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtyhcdm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fuemlfgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hifjfrcb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsgrfte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xurivsrf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzzztwz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhvqnvq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpouaqgh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxivrvk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2immgfwxj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vugiqjqx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdhsqkc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdayskov.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmegircf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrocmyt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjxtncy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzbdcsn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzxnirp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoyevxx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrnpydj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkmgkib.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlrvcmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegoqjx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2czfciwtp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaojpqrw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqqzvyi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2erjhfmml.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfyxhyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxrjnbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rglqcpaj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2puobaldi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfavrlo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rewtchtf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nbalsqcg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnasnnf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyydyiy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crfbhvfj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvliexvd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlepmfip.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khpzsxkm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcudgme.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nloeryhy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuzkvyn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzszwhbk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtefstbi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcmdxqc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdncwyat.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2poqqmtcd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjnoacl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzrdros.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpsxbql.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiacwju.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqonxcp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwigploo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syaogndx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oavlezwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmdoumx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uaohhcfo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jevopkeq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ievuojxs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwegzetu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uahgkyon.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogauci.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gaitaxbk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdazldop.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eucjfyuf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzejbcc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpqsqjq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qxupukcq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dqceyrlj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gukqqajh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijavixlg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnnrfdg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gurqxodm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfaidma.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlwbdvy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfflnpp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjkjiog.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyrkrol.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjzhwmf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jttnzxfa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoqmvvc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmbqsb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsnlzns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqdhfda.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thcgbpxr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfheonq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbxazqt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eourqbvn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tgubpydk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgrtbhl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dbolwcgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbzcmfe.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuobblc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsetcpo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2drdkoriu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vzapkkno.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjflrss.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtizzii.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssymkkjn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylobsrrs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2begcxafw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvgrvh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgxvons.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npnmiibt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hoasbprl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mawhwyta.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zodhbntr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcolbjmq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhhgtxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbmrrfz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kedhfwzn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2somtxref.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlnrury.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifidftg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyuryti.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bupgrzun.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yiczjcjv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2clxnzheu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qnafnmhq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dllnejkj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnnoscz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jezdjdxs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xoogkyzl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bakjtxwa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhbxmlp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sodquctw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwhfgiq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfahpa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fopqmxeu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsxdcby.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqwkvhe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2babrjqur.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iginkxke.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sgukdrrm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iybrpxzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2edymxzjz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cameeblj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xzshhxgs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilztcwsr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjmijpi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2koswupid.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqqsag.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fifzuugm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxkygch.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvoujye.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzcmlz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkwecyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzxxvyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsvxpma.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsmlnal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msmzafnp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uykgcgui.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypudqef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpjcvfu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jroftmfk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhztfbdh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbgiqts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rltzsodk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmucblt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbguklxd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wejlrekq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kldwcohm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgiindr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hagonxpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fteetveu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yicxjtsu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdebwth.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oaktrhpg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyyapbo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmogfzz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmzyfkc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqdzyku.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2waoehmwh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avwkvqaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkhpam.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffbpir.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwzqxqp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pafadiwu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbottgi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxegnsx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hblvcwwq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxogymc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdnteqn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whccflim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgsbbrw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axxpzkup.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvvpuzj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qskvdpyy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrnzcgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tltsfbbh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhchjags.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxipfuc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wokzozyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kagusool.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcuofza.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvjmts.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqsafpm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhnifcn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjxilnf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2egsgxsfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ieebpaid.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgxfmil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rremxdel.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmvojko.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnhwwas.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvliaxgh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2robccoeu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomnaryf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyjtmmi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2myjwxjiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yidiqinf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fuojzoxi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qftlkefe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqstviy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hyriemgg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bptbtlgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfoctp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaoryih.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmnrjui.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecibxtdb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iauqhswo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrxyyun.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgiadfy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2deshwfak.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzfrkvy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2divyitqf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilcymkh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqejobxy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yooxndvb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxdtxyp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mghvncxt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoevmmg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfhaucf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgwvjby.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2coyedvpv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxnddnj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2awfotzmv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2izeqwuhi.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngppbvyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikidkzib.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgosbffr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvptquwn.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qmelfdla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaotcusv.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzxsmph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyfsrep.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyoexvl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wctzfgei.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwiqaox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2blizgxpt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmssyep.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrcmshu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetxpxnf.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2omenygoa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aswwwgcz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcorwda.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxobpud.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2uushwnjm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2acptaaqm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxxttpw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2khuqckqv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhniqvtp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaijipk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxihmskd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2evjmtsoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkisgzb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhdxksm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbfdoti.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjebhto.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2goqcuoos.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2osblejfc.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dicwwkww.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtuzhno.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgxcwub.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfroopld.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhymifl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvedirg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjjehuh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oumfqdju.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rntnzuis.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubdtwh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwtnawi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2snqgwbwl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfqrike.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftejkxrv.html


<!-- 参考信息 -->