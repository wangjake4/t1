代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iixvxauq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtwvviv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoponrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czcogkgf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzkqeea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wasekkiv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cahlprut.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtisuqvx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2acgnqlqe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mruucnoz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvafropz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyxqoio.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshbuuc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pderrjbi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jbikgphv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkvwrmd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrxbwmw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bvygwtji.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmamflh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sycuhrsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2astbcfct.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfrrbey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfksbtt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcssyop.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtjanqu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzcfsle.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkzamay.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buounkau.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwhmfie.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbkdign.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eltufqqd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grxljtem.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajscsgga.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lakyoaqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpyflxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oymraytq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htxxwrrv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgfwemo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcadhcwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eohgzuig.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkseivnz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjmlpym.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhbbssf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjbelfr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okpjlbqp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2btkdeaxu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlgvimr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwllgxv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqnzld.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2giispisv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glmhvpdf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuhpwkx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbpnecb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwebftqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drytwxbj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsudnxv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2isxfjjxz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tukqiwhd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigedfeo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wovuosfm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gfztodgo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsybygk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2risspoba.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiouguc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmzbxnr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dskrvgrb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgbxpmm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrotnhf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2znuqlymq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdrcfmt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xillhszm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiagwxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnbcdnb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfgluqx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ejslczar.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2envcwqbx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwaefxw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yntcbgmy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylogza.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpndxci.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfqzhkc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkrwjcn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhksorz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmpkvte.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjiyfhr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhfpaxr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvkawum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkxclsk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbobkeeb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oluuccil.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgbsmoo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buoeirji.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwhudeu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dajokham.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufouofix.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkotqmrp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuwhhwv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhhzqwy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuqwjus.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgnwtls.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjscsxyc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2huxrsbei.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrwgyzv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifuuwbb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2czxwqyaj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihokmgkv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgetsdl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjibpyd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2suevvryx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2itktjkfu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyemqrq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqtnsbj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lncjrewm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lenrfdpo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhnfcle.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunwzcw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhfhewl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbngwul.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzohknx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddlvdrl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fiezqjop.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipydbsam.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxckgfjc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkisfvf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhlbzhr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejngtxnk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyjphmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxbdvfc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwyted.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeaunxv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2odkzspvz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avmqekte.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaahjli.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfzlhs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgfres.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcyhajh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxuali.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwlvuqa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqllukef.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfonqid.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ehygmjhg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jegmniie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdijhff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2drlzjnqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdimngqh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nopyxujf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsmqhmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbipmaj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvuepfn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjpcnqe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbeamiu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iepgwvmw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzhedbn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhnsgan.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggtlop.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpyblfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2frpkzoar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okysmyuu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pltevhaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iupqtmpw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhvborz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadwmdyi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwwpgol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2icwaawbh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kktshzzj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnupqdz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoqeojb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhsmle.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqyywqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anfnvqwk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsbysag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqttnnhq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsscbmi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwpisov.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvumtq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxuwmz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkkzlox.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xonimvif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvnxiyg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2podpvflw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2agkdvdjz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylqfneq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdubhkkx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etiryfcc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecfuhv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjskglfr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsdkusd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zybcipfs.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pkipyjbv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2spgygxhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoxerpl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyxaykt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gppydrej.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2guryjzpg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioovqqpg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wztvonyo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2frkruwfm.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvfwctl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xalxkbwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjwpugu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkhlgdy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdlyxcu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfudjrwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2eihukcms.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyimkfr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zydreibw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtagitgd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwwxfba.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlmvhlx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeaftak.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bitlsizz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbgegj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqrppjx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zedurerk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taqvkiyy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2frlnwsjl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2anvscsym.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrgdgoe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ombyqbry.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdtayyq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjuqbms.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpfdhr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtytiwg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2knjggxpd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2spfsjvtl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyudkwa.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvbjmjx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaqaegq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwwyzih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkdebgi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqvznng.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2covwnymx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwavzyk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpuyeez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgcgwen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxvtbii.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgtrjvh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuxkgec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbdmikj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjqhqni.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tefzrsdl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lunsdbzg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rqemubvd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fxylscyt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnnwfit.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbrgqqo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdrzoyt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmbcpcb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kxswxlnx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqqvxx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxglzyom.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vrudbaoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmygxtwu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqnbow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaxgmhl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2veaebnbv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlifzir.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2awxikaji.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjfviaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2advnkhjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzxszd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbojgmdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlupfth.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aplmnvro.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2quiewnkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkbtijl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnloifez.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvwgxco.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhfxet.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkziyfv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnwklbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaqagch.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxmbiji.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuuowzo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jalkbbkd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvknhqe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukubmfuz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzcoyak.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypozwrun.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2smsozyau.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2figusxvg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhdmbwh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmppfhf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qurwfnyz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyrdain.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2drendbyp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxdnqxq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyuxbut.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2exyxcrcx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gahvqpth.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcxfqpb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclylxjr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zutpmjkx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrllxygi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2otogbzmy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkuxysu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfnympg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpdairz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwftqi.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgflzbu.html


<!-- 参考信息 -->