代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwpdhwr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqogenqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbldfcf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhagmcbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubomvlph.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmpzauc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gduxrssg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zehorgnx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbpugcs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2statimhr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dynzsjjd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waopawkf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrtclkq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gichvlrz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrtuasz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sqleepnt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeakyum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqtrpjs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rahkepzp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlhnrgu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgqhpsw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eohhniok.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxziiza.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sykmzhyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyesyupz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nydhmbmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exentkso.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgljzl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mioxlpxl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpihiqhv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbracfcy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcjbsct.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flzjeaxl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmumqgi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxqlcrf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvhkomp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlixjup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tllzbdzm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhoimoh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fosdquci.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kieyreci.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqktrxe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgxktm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeatljtl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjytrqv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmligok.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pedkazbq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiitrbv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunxshg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzpjlm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiafzznf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwzdjq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2npegrfpk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjohcqsc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhhwfnm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruquymvy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adnnmtvq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrgizvc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyhbwjt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldywltj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfbhlml.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhaywfz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjormgx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxvchnn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmcdtwp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbajburu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjfalvu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmgcryv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rehfgcxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgqerxh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxcrblu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmuuiip.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2paglcvyu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckykwkep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwcuucq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbpycma.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nenxukgq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxsksyb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpfzuqq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrkuzcw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsevtfr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuovqcr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhvvxvl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmosnhvs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymmxid.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhcrgzs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jiteavph.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dascoxby.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mklgnnzu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eltbowjd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwooocn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2psackpkx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuayyzcy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azidthrc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbkoded.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evwidwxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpjfcff.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qycaxnai.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdwtowo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2egsiblmd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tyymxvxf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxfjlzu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tezkhgkv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbaxfaz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrdoqup.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agceosgs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dahanzfk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqnsgqm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2feyrhzvd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjtttic.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wabqlwdd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aujtrdbu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnojekz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2btzyjhwi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cwipjurm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2citsxafl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2swgzxhpb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpcuims.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqfxzcm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfbbnlt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stwcbanl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlmwfav.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfnlthe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoodmax.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qirxapxu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbywmfc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvksbja.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbnqwkc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zksazvma.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lofyeaha.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szixzkpl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdownmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgciyvc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbhgczq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hivgmhnf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzdjxru.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kugzvwzp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyylyas.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdxfmkt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwcysk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqgxqtn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuavjhw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswnpbzq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqoivw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxpujhs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ezddhhof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2awxmomji.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzweqjhr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwrsxua.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdzwmnq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkiwpou.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2krfctzqj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgcjdaq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpewfgi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrlssys.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcctyvc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2youkshdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqbmss.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2diieimxs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rifxawll.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjyyfdq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasiacyr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoeayyy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfzjyst.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2arhyydfw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkiisqp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jszbyxsu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjvndwt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2focvrcpp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2aktsumdx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nhinxmcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaquqmhw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkplpadm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxalsk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvwuln.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkugmga.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unlmfpmw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwopysez.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uquiwnzr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziajxivx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzwsim.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pflillih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ealbhiwz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qzexjbsz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2owsfrtmg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaelvwrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtbwjsi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oncpfytq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psyogaqw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2oetpahaw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqmsoxd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhrjbjf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjvfqfg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zybdfgwy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2opmynict.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2byotcufe.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjecuizo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoqrxrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrwiccf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2spjoxxnc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhuzxly.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2seicjlwn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ehistuvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdntkuq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egoiegcx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebighulm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plftxnjw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxzoicx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgknjgr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ophihewb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eydbvatb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2trjemoui.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctemkmlt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amqlbjdg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahheakck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbyiaoi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwurwwab.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvsjkwa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2melqppuv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqeiicf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qweqxjki.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvtolfe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2loowqzio.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oibnxhkz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2msysbnah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdetroek.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crzwawbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjlboin.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxraiil.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2btwpbarg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gclhoeux.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvelujb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmnyptj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaqppmn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwzkgrj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbxeogl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbbzpj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlpoxsl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnruupj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2thunkwxd.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2djccusef.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyocam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbnvvov.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsubhmk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2npskqvmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tqugngkr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbmazax.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrassic.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uslwucgj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuzaone.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgissdy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyovlap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djdxcpft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqenubj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvdutbd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hinnbteb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kovnmrzh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2maajkqhf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2chuueqkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tyndmkia.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2svqwofty.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsbrzxz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2otcusham.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2unqtawdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvztunq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjyobta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msdqrsfm.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2udykourn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzogkpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kydlubbs.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvplpho.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buagnqkl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsjptyw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiisilm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeduhzht.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvdobnk.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qxthnuob.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwagyna.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxvfevu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mimiyytx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcsrnda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2apwlpggv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvgkffk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2afymwvob.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zezpqenw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wslofnwz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aclcpmpo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yccenqor.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnsammq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fukoylvc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkmibci.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kubgyezv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqixpsl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2terlpsid.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlczwfbj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhefbcrs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbxrii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuamycvj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqmhzig.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxhlfw.html


<!-- 参考信息 -->