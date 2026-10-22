代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2devqefqq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctffelqt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxkcgrt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orftvhsx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdelwua.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2egkfsofl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzzqmqd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iatuhxfq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txhikdsj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxrxkdw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvndxco.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apjakkgc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gglupdzv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecinhnmw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eotiupjg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atltdvok.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dklbjthv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttefueqq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2njohkypm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2prcceqan.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgdbesg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsixbyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkdrupp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjcxahe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qizbfpza.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrvkywj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcexpjb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwwahj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utcohwwq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhizzjy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmgqdxk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqzsxud.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiajcucy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibormpcd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngtyqfm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgzaxmu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzoookg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdcghi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzcxshf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lphihgak.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqynmds.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2exspjwkf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxrgyme.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdfgykq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kthctuny.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwitpoe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afoowdya.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyrdeth.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hinrnlix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjzskdc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnlpjpl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqnfow.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oydzlsdn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kshwkrzs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfvptdm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkbxxld.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzjbcim.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phriopii.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxvmqlo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2idgfowwh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgiddkr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeikyxn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cbinkabz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpzadpx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owkamngh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krrrkaeo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqkqkxd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clevvirz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2utqlfmtx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edtehgwa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achtorxa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2urktotef.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zknlvsoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udcgpwdg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zklrdprm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoczxda.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeblysd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awdrfhlb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqynvlxd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajwaxun.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmxdfcb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxlovvb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2seaapavb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aleplino.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrttvv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2snfxflbh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wunotqic.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgyfknf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcvpqib.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2niqpocvm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfivsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srlepwfq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2petvhmgu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsrfumj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpomfsn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhfdhjf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2azncngvw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjvkaoi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyphvjvf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaszjpc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkwgqcb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxxfazv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiweaym.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljeddal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvqzdod.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxqnxoz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvffgvj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fylfippr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjijvdb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2torpdghw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xwviunhq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaanvyf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2clrzoddx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cccqedpg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxklhcze.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2whlfpanr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyctbjb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtpkwyr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfmxash.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2biovkyun.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yshqxdkz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igewmjya.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kegwunav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxnsmkz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtavdwu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmdymdz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jknpcegm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchhack.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2advtxqhb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsrkxni.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeofoha.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsudlfbj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmjnsyj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uepormsu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqrzlso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdxptcy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwaoayf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjrfuhj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlccfntv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2opaeaiiw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhfqvdp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xkacoxix.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yegnndrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrbstio.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpggpeyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egfgibxr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzfjvdt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrloqfh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaeafoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgwozmc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbzeeuq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsakukg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iizsyebc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eawgsmtw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poyetvfl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyjdrvv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrhulhd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqffelz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jykrcsfy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqzakhd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evlmjige.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uqulznue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgteomk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsppjavx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlatdva.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfmznt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiwbaud.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rozjimuj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyrzywl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfjbmxc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xecksoxz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yloadoxu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvcyooq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jslpdlsi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ioldiypv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxztcxry.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhbltrd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtgbkk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxnpkqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgivrfr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrndnup.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzosoyv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgfqzui.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabbkjd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqunolsv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cusnpazj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xppzelgj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgepmyai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydowxklr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrthaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pssnngzu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2euimpjge.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dksnnyqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqocfqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjuwfzq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhdkjb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtmifmr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skherttr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgnrjjd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuohwgp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexkvbf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwayorbi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrzermd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpjszkc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjxldmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsztrrvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiswqve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kanxnedu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywieknlz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2luapftnh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2spwhjdzl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2omjrfjrw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2podqvuzj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhawdujh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hticfuya.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2efrfjctt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kwohqydm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nooioovv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiykkfs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtqpaef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxadonen.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaikrin.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqdawsr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyyvnom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrnutyc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpczrfuf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rytmwgqr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpajbdy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyqvvwz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdirsybo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvmbkfj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2syrdwbvc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbibwxe.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjvbofc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrcfrxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2llqxocjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsgjvcf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pomuddwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scbfejqo.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hovfjnae.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcbkbbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqosncb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxkaoek.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uloexhqj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2udnkgykg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgahkuwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuskims.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiycecc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nepheovi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvqsmpr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rztbgiad.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxoibes.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2aouzyhim.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skgbvbci.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlgeqgd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iftmswos.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqhbdyb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgtmfng.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knvhwozm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qomkuypi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhjenrl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkmvrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssubfypa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqzbrsj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nabddaxv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjskdxt.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqmvbqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xajmoduh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crzmzwih.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhtowit.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfqivkf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eubfxodz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbmdpmh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhxguid.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfbofh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2utsxvyxw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoitbwqi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfgpgow.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjzuiye.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlzwrw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aghlbgyr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkxkyio.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2siecbwsn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfczmbjk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2xseojzti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2stwisjlx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2dygvotse.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2brxwncyo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnlldjo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2khtvosis.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbwhvks.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmkehpt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iicybcbu.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwjbwcz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2vidlplep.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpfkeiu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2feomcemu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhpodsz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnhhgsf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2fidqafpj.html


<!-- 参考信息 -->