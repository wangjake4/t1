代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeooaip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2upoapcyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iolbjfxa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsqyxdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpibtsle.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbywlhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbqqhaq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjjkvuq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ouognpsr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czcinpmg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbdlejh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qydroblq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loywbbrd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgmcflb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkbgqfb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqarhsc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwwwja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tziadmdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pimymkuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjajndym.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cealnbyo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dihcfgbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2womuklaa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dstyruqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqftrco.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpzogvj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbuivpo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqwbiye.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iljvgjwz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oktkddqk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqagqmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiifyja.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oysojirs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltceytte.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjskxgp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2twzypmnh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtkfmtg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxfrarb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvclwcrq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrzovd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbplnuyg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpeiswk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdkdndm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgqcnsf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zujvnxkf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkpurot.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiguwbsh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyqnbxa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyifjlmx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbhrbhk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2knlaghta.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjeiwey.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2toekccdx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvtjfgt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvygjquf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuzdbmb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqbauqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhglvwe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzlhidh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtzhchb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rskztthu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxeyvkn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhzajwy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nytnrccr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eutkcyzg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdnjhtl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nubrsisb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2slgrmrnp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kegvwuti.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlltxfcd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cyswaebm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oocuyqkj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eihjwskp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsaevxi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvhmaqa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdngabs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yahiskgk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gndjzzcj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itdmkohx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dluhoudu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjeiycj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkujbokl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xudatslf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlzyvga.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zihckdto.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoyxwyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjmwyoc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrqvuag.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2safzhvtf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpeazqh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdbhxhw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbmvco.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2frlngihj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbxzoln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2udhdfcez.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fokzkxcu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlgmxsz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2obraaccd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vonnpbzw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxskfckj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbqfpiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxuiewe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpnlxga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nekungck.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfbnuyb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydxzrnz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvckpfst.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xqekmnru.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqhopuh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaoinnu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctisxpi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyuthtu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqaxlxl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbszrcv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzmqzmt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjpitk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpzgmk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjzwqcq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjqjri.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2smmirqqb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsvqiwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2irawnmot.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwqfrmv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvkajtn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2diwkmeqb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fitiaooh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhkipvv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmzkaex.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdvconv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrasodkk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgcvkvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2akcjzjao.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbsrbqk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbraotqy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eocbbbaf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fppfjlnc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yevxxkto.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfhedtx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dimzmnzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eagfgtnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2toqbjdcn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwhcsz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ficsqgzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrdmpur.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2umubltwq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmiajzl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjsxvc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hloeqper.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2houkvhsd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzyocbu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nylaqrbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clklcurz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxztxys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmpiwvg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjksejv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlohjby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ianchrwn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdkicco.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdoexsl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxumvngo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tptyuygz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtadvetd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpihmveg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfygvfd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmwifwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawinboh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmtntyq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshimfgf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeaqlmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaptcaq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gozfrsfk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2camjtlox.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbbwnst.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwasmjpp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuebmzvn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jajwolmc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxvcpso.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkfarxe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimiamdq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmbkjlx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiehvyup.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxlibfw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyxfuvo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vycmdvrz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gziavyed.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuakizt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfepeaqm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwvlrrw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khqtihoc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwwpnfh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnclicvx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lzslnxjt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqiorlc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzohciwl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwzctou.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skrbjfkw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzcxjdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpywrro.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utzcbsdo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjacepp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxtlttk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolukwkb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtxnwmu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxnioam.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2enbdbwvv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsusgpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2johehzgf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzlwdlg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhptesdj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2puogjrxd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alepyrpg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkpmwjq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpxqhew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2euodekiw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxthhtv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxbmpdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2txcmcsqj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyvswa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2oidkqywe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2obyjezmc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnnqnnn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspoksfe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2wctyoira.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxtiif.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgnbuqp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgcuqlk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ihccokax.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jliswrxe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjldtuh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvofgqlz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdcxnmv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyarcur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oklixrnh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaywtoyf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbyfizu.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kzofopet.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjxfmbk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2oojrwftk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xdedsvmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zrruiajf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgwjpul.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkzjkqb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhowosbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgolbxpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvetduma.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twlvmksb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvfixww.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nexocfwc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhxqcpt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucdoymy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdiuivs.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfngyarl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjovopdv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmntugc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovnrwr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkajcux.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cloytdgk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thziloyi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdvzzln.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2inosmnpj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpgzuf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2beodflps.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomfaxoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2flearuux.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkguseu.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmszff.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgahgdm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbbmzja.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmthrhl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2llaqahdn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcrzicf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xontymhx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmdpezs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdirmju.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlsehtw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzadrlj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpinvygs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2avjuoafx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcvivqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwkidgr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftocjxsa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcngybm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkgzomv.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zusutotb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktesvdpu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmswoe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkppgtb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnxmsvu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgggkps.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgesdgcc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlpcmls.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mydsujzd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuajeiyx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaogbxsi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipijcnwq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlrzozw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxpjqxu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwteels.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjyipyr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2clytkrkj.html


<!-- 参考信息 -->