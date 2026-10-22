代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoojttfm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsikmof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqdtlra.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnttijx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmrgfun.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aptyupaj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxbrhgz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtjmput.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfqcuod.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqituzd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pmesiolp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzmcohp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhsxxjq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oajcllri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eelqaegj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhbbfwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhufaeop.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvscpkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxipwdvc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2croiiicn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgfpcgi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcomsoif.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpthcfx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxxecyx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scqmvcac.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuhydzp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2temaiccp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uozhlbdb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yueiqvki.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2towzxeug.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwalnkzi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxfgneg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoslnjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdvoqxl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bivtelhp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqpclb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qstivtlj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqcnnjn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcijuaor.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzlvmih.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcfphzh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2buhcijfh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjdgcyl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxagsan.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqbeibi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqfotj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjjzpbc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2arejqauw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pursbmtz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnblmwq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyioith.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvrkdme.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2llipphav.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnnqpug.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcgcolw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2otnudfnc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2begjjtvx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvbypdl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjhrrjr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2injpbpke.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwfvxqs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpthnbr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukurnttm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiqdiyj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bycnkcth.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gelizqmj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppzaaql.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akiurzaz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pszmshel.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atukiafh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2umfccxrp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqentdt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbqwle.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gggnnhyv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvqevzz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2labmjuyx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuuxjxw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtphzxu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpryewfq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2olqyfuqs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vutqgleh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjgjrvj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2prfxigdl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvxmsfd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyrfgnc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzmkudb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvuphfs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sahztkau.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2drbpzbkw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxwowip.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qylesbcq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkzkxmw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gzffzpps.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcstwrwn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvihwxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtxftuh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2coszaepu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cakkveyx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfujgoq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlfzemv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uiavkifx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftkuxd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2elqgwjbd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbunrax.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lodmuioj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjuwfvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwzhdcl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jwecvvsj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrdubgo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgeqcux.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmcywtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paemygbe.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxnhdwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxckvwjl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zweizffm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmgicor.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeiltqb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vryvghfy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmdxcy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dusqkpwc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkebsbxh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coccnrif.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkwaiyz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbnomop.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2picfjvhg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqknkrj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsqbyzx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrrfilf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqydjji.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhcvgij.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlrbshc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxvtssu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuoucuz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaolcyt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxgzeqf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lpclnmst.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwwolfe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zfywhluj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmgnfgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2obpiourj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvurfft.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtmzmuq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2liazeexf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2shtysewi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2klxohkbn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxqvqii.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgchsid.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkknpwkh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sciwgzyn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrfuxer.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdgldeg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nthublzc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtdkwnh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oshrnqba.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsnzmjk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lwruhvsh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgifdbu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxyfcyc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpikdan.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2papiebbh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eeesfjpw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2agulpnzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qiobnvge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngafpglj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjelmcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgobymq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iotwnplb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qotfprmk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqasorg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmtepfr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujennwlx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjjkten.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2umasqfwz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdqcsta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxqaqof.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxmwwnl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdrchap.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdlzddb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uixwwawd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxurie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuizqcg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vemkfzqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnwqhpb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnmcdsg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvijrgo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrpbnrz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgrnmal.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xowqgrso.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jungjqjc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvkeahe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoppdlm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqosrtld.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2efhkpgkv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tagqkego.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uscdmmrx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olxpmnht.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpjyoab.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkhrsgd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwbmvzw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfyqgia.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igzaydsn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsmhcsn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvrapgy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxvcytl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mymugwvt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzdonpp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebobirbx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mesnzzar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsmwdpg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xzftrsyh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcjqig.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2gymlrihw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlqlfcm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfwimdm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ruragsnh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2perlqxnp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiepranv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoqsqhh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulmxsas.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwbhfwa.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhgyuus.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvhklmb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpkaswt.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtnkqeo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmbvrjt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrkbpda.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqtszyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nocovrbw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2htflazgt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yqajfrdc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmxvmxo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiznvny.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2obovgqtz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxbvjoe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaboqpjp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2obdprdwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkhpsmk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xslsoxdz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxidxeu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhbywxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpstej.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2nacrcbex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrxdfhi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwzxstf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2szifjqfv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahspda.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpucayd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gmohjyzd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2phjkcdug.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzdbvrj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbuthyg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qjouoakj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhelmwp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmjmrnu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxukox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gugbdccz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvdurym.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yakfazaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blndemnz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhwgci.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitxwbcw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ducnlhjd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdilapni.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwmuvo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmwsunc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowaadff.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaezkyt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdbxuoq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2utykrxwb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzrdws.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbazghls.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxxhci.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkomtooy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsmifpc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaksgdpa.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdjgqsq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwkubvi.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbsfryp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2josmosfp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxdbrol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2djipjyar.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kopexwtz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hghpvdbc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgtizto.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmbbcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2uejlldql.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgutspef.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiawywz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaatmgdv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfumyijb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2inoluxpw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhophqyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpchsia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcnqrqi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2menehqvb.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbozpsa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrweexkt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnawjrs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmkboro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmcyyy.html


<!-- 参考信息 -->