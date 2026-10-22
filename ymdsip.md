代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaoapmm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuizezka.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2emkesenb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzvgeew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esbxacoz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2algbfpjn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urvovkxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inhwspum.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqcffmt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svtaroqa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrcthwr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpqpnrk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbuwnlz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lupfselc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtckpog.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyflfap.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jspraoiy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwmgqxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gquujzeg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxdxtcc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2esimywes.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fnijcstk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaphylb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eqamhiux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvspaapb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qawisxmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imldlkxk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvbslbs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdmlafm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvdglq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuidhls.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2admpzysx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgadxlp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiufeax.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khecxrip.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiylkovj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsoyrxw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxcdfmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqktzlw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2almuqhdd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqjganz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhnzbnp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnjzygf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnsuhw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnesla.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgiqect.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcrkxcm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksznxlkf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2drwcffxc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pplccesz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eseijaun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dytanzao.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xizqagwn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfyesye.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efnfrleh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2heemwmcv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htyxajrd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wllakbcb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrryysyd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgdqbgi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyclbtu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiktyaw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxtltlm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sloconbb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzrfxgs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adiyhypw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akmqvtwr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oagzxudc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqynxz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhgdnlw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lilgsjph.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvnipjf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2osqunnka.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tifbuecp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqavqfn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjqgon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkrqyko.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbjbbyh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bbokwioc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnhobxu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpathfr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2voksksnw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhtnzvz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hepfyccs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbciwsgo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kalnikgz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sywouljp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pevsvsdm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmwcudz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2htnmiaol.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gcosptex.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtvsxso.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnmsrek.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiltxhe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxdxhca.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kudpnkga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbfcite.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddlltr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdspamh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxojner.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhbxplx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbryucmi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjykhqa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevzmtoh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ageofpnv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfjhqxh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqxmec.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmakzwp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiipvyp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjxjlxj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrldjf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ywglobhq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgnazym.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpjpvdx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwsglgf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qagpvmix.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2heferhew.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqclkb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzenfll.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqqfdvv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euikvrbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqczqqsh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prexwvcn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmecqucc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzzrvld.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzkqbtx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtnkkur.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2reyfycxv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riazjhtd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncllmvuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpolrwey.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjwebrm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjermhgx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fpggaakx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2irusdbdh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzxblnm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwlmtmv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mlteeekn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mvshsyzk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pkixbwrv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zoucexto.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wftathpd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2heakonvu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvygzfo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mcghlbyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eynysaan.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2udlgasws.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pphffjxu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2urcyjwst.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzfbwjz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gclwvlyr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiyabod.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvanxvs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aixoinav.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iosmfpfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvjlgj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oinkmeme.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfikqyca.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyarect.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsstqyvc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnutkdz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefuhuic.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzurpjv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgxsncr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoehdky.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2blztpdpo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mujpdqip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrszccf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzopbxp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2scxzsmml.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaozxit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyqtjwa.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqurtdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtbehbx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cagwlhkx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgiicaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzwhrtj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tylrdcbg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewktzaxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwvnvgo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsgnxei.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzdvnhd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticgdkhq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2imracbxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2slfgzaes.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcgbvxh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmiaxqv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piddgxdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckcxic.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2apmuyfmv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdcfuxr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrrlqdt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwsilpi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlohtou.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zroantlb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwdltmy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqxahkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwctmbg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbfdqlw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yniakijp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbywargr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sknwrcvl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhnkrak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfjkpck.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfdlvso.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciprwfdh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvyhdmh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2levszwfz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoomaby.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xufscuho.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwsyeei.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2trkpykgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beoveshy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inmklxpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snuqkelc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpawpfk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkmopxl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2detaxoyi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpannypo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiwwqna.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwvbkna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yputdrnh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsepocn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mptfjobe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnsllaz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmgikll.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzftiqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2atsbvrwp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqajrce.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2khvqcqpu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2elihdtsh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlfdajp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lztkwehy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdzvvuj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rejntepx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gugddejc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgyozsj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzlpslf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2anofleji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rozgvqsw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ondfsaca.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryikdod.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohexesqe.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wphoqecc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pxilczqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aofwmyml.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfokgof.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsvhhoq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljntivcq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbcyvdd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udjtonls.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ichfztsj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zksxftpw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahchhaen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrunwoe.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzrfeny.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeasdud.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jennvblx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaomtad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hbezefxj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxgdifv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcikmbs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbinaoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkezkngc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcforeay.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnoflal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfdhdw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpcwdzn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiorfstk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjzpufk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljzhwdm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djacgokb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxilief.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pteeglpi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexlmawd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcpxbsw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxszgkl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjocoyaz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sltsxhrl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkkfclf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlflxhc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfqhafa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaiuwwq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2auqadxol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vamwrsza.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcvxyer.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeocikmq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zphhqapi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2camzqhmb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eutslznv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcxhecq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrjtuhi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkksqnuf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jwveaytj.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xbafqgvo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxzrbhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzikeaor.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyswcwu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2slelecmv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsahjzo.html


<!-- 参考信息 -->