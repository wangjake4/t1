代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wptgjkzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbvwelk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tudjitmx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkglips.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lojwfxdm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mihodgvo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmowxpdq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dleppkmd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcwhhcd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cxflavlt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dqflzlvj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxkdpoj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oooeevci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzylpwg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykywmkct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wzicrgco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcangduq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbljxyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpmqoxs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uoythrsj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thbnndmd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmfeolh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyunvbz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxlrqwg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvglahif.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wccojcog.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrdhpde.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmpuaxm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrufzog.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuqkvzv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfofhle.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpodnkz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agbazqse.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxeenjm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygagusoo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpiotem.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxggzeye.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2odpezine.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwcszl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnerdyj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cynyqqyo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nraggygw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyujvony.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmyhgre.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2asiooglh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aznivofy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2utcvtsgq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kqldxbmr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochpxkxe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszbsjmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suuiidpo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seursrtr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2swenyhiw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxpcxkh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnqyjky.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mllmaqmk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpvqfgf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utqrhpbm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrsdxuu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grejmtbk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmcscwf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fletycnq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdixtbrv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atqnqnak.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2klyjttbs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkulnmtb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqyxrtr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlxfcul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djffldyx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvobku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2punfwlaz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slotggeo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtqovca.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxmlzsp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yimxtuzz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnexeoaj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhnmtlr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrnupzp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2miywurkx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhuneyy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzrquao.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cctoblny.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbambuh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kstemmpt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfelcxhg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bffuimhj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xondglug.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwngmrtf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eojwdijy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgecnzr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edivlldh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkrgyam.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqqkvhp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuyzgcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sufgobrr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmpkph.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuqjlue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlukwvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqsveht.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkgwira.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2barwrmzq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvmoyii.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whzsjzwb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoeqwfr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2udrroxuy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dltkwlao.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2aduleano.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhbccmw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vftzyvzi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnebwbv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfdfroq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcfjihj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goryiigq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsfcdsp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrkluul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhshmjdx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfolyfk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopgdurx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmkbmkb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcgkkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rinisrwf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzreszgl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idettjly.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqchwnv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogssgiee.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjjujof.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoauiip.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvsmnnq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2csguluvp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zudhirbb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zklexcnq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sosjljfz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2menxstgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2phydurgr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnqsolz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2egajywbf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqytxnu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaxbxyy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbwrpn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdcpjsy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2irfujlmw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrarrxa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfsrjgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtvclr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cogsxjhd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qttpqipn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2raudqnee.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqusnhx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxsragv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeqrixd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsbqawm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsxwvlk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2chpcxcsh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwhcdka.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eneoasfb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cykcdvrd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxfluc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pecpqhjl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcrthkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2phlknnky.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzwkkzw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdojwph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhedzlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecenxdcn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nyueqqkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhimgjsu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vfizrpzz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzzmbmp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtperzgn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkkdyf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvkzwhv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqnerwm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hiehuvuv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilebsiue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrzubmr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2agzrxnby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvjtncc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onnhilvt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjayzjlp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdisboi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usztjgpp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbhvgep.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jliolkqi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkorpug.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcsnodp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dftnpdtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2abjibeyd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jllyifdu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnxtgov.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkqdqcw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtryxos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtbcjmf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzpgwry.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzzcgcb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2abtwegbb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twggbxal.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrchzgs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eginmyge.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpqwvsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcycfhu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blunxvdo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrqabu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrklppbu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jhagmodo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isvxobaq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzntgpa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxwwlxv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlccsvuq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdkysmd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbgpvuh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtprwrq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2twzjohkv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2npdsyjeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbdcnkg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrkwuhh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmoyvdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxodsoqj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2flejzvso.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdabedf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxodznx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dedpuoai.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbodqilx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2feqxioir.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklkjans.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vputnnhw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrvycnz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlpwom.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyeztvr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzysddes.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqlqleo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvxghye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbsfdoc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzypkmm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpubkfc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpanxodu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uakxmfpi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxqbmvb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ifduidbf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoegbeq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpdczdr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2axglrvko.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2troiaxff.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2optqlwiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkwlqyl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrvsqje.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfwwwh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmffylk.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tqichmll.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2racrapma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtprqgo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghhqpm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2glntbsyt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptboqt.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2upuclasm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfydnohi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkswwqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwowheug.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwazjqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2colupxom.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bmptkwym.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdmaxme.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2irqfhkou.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gggfkhzn.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhitsji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkxfflv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcdxymr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lymmhvna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2clxirknt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llqlnbxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsyquwa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqreqfoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlhlart.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkbkvkj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxqcekm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhesaacq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmzrmhc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcukmaa.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xupyhuog.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamvyatb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwzhkqd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgswpnom.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdwuxtr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiezlko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2qztajodc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2waicqfrg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyjqsel.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enzyicqq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fptcdjfv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwiaii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2crqdhhck.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbrdrsu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2whwyriyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2peblubiv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lazlyoje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnypzluf.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uipyfnoe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdimquev.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmhhcxm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdncnozs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjmzodp.html


<!-- 参考信息 -->