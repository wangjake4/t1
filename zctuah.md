代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kicxtfil.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrveeld.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsupvfy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvkkjlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syszecua.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjaydmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xycmtqtg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgehkcs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtqtcb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpsliye.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkyzfml.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqorotdn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfkdeao.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pspgqswy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thqckrik.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatbocq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kervyhzu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfujivd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alxlzfqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqtekxs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqhscxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csyutkci.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchosfui.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjnpvow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsztvdzu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzlebir.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvianmet.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2blbikugr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxjkcl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqrhmwu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpnyscx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mraxpzds.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aormpkru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pszpfrtc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjetamsf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqmepl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjxoqw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmarhnv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrbmqap.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shprhjbl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhulbdmr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htosmrej.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrtnuiv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nachbuaq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2psoaxvwx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biugavgh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxhfsdd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxwgbtk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lblovgup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoutaqx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2beqhlrfu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiytqza.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoemwcg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2peyjtlro.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjyrvw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttdvdzn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibefdojd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqgpav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcaouhv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofryiaof.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2iayqkdct.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cltxpugl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2psxhojds.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2txtbvzfk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopikqh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqhblvs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssezdpzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeecyvh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjejdsd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtozosr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmuqwai.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yuimeftl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noxclpks.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnykmypw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaruelo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtmxjci.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hegypylt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2noepusnx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmlbdma.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrmloh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkvsauc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywukchrl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhsezvo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmkcmkz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcmjztj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjvbgss.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqhygfk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzwfpfe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kevesdpm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqdlxrv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bphbioyc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjyknlo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xygyksrg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgqwndm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tijzshor.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfhccq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqhqlmh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjhofx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2igzefkyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byglefrm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmryjyik.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfnjzlx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ducpxdeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpmkxy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uiijfypz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrcvxjd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afikndgn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xivztsne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwvmiam.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmbcrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytujgrkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudmibt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyevvph.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acauotdq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzoednp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igeppyuz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwywbfjz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjlmtmv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ieptgziu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtftnh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dowqmkgl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2daamnfvp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxsmhaj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjvxulk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpjzjpr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fetfenxq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhmgffj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2stkfrlqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjvioiw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvmjvv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoyizdk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2allxldsl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2erirpfyt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtbetai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2awxbimyz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nessgovw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfoyyqy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhctaqo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lohsauuo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvftqyxl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuuqgrq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2olfiwzia.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cuttyfzk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgkpuup.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnehsmmu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmatnizf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpgffqc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxplqik.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqbgxt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zecjnljh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxpckmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgktkuw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjerbyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsfyftb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjmxymf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrooxms.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjdfelt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brfxgnbo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hclroasj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orcwmlkc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcplfcs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxokuqj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veoxvwiz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2grloiqwc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpiresy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osqrasti.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvtlyot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeounpsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmrjffc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjgrzgt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdmsbgt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysutmtzl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gsweptpw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsupgmc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2unhsouqi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbbsdpu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mthotqoi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nubpryrb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gguflhdw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2asildous.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtnfxrd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyrhmcj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiyxclz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgmilwa.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cestwyxo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mexssqts.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deamwrad.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofukibxd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulstwsep.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plbgxqiw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfhkdaj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uitewlfk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etjhvwnc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxmxjsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuxtqhy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmlwxqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2drejaomx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2anqxxgnl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyqnnrw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpgvvzj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mauoadqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zulpdhxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jukkfcvh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbfpuck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvinewn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmmxwts.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqhiyfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iymuamig.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dycayocd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvayzxgq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjliqko.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbnchbp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjuryun.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmdkhx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2htplligo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfddkjn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwotwnei.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwkcjtc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2knchvanv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtviqlny.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cteyqrye.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrercgd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2awntmisl.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckernjzt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wbadzpnw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2folwrumw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2klqyatgh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmjcasp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2havibhgk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqwuhtj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsovkjko.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlkvcge.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cgstxehi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cilibvmc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhispms.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxzztrj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rymeyoko.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvjdutk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuuulmt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxnrabz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaztcgk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbabmxfe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmanyvz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2koykniwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnarwxao.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqsbzge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrnbpuj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbgkuy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iakhqojc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxyccvq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirznhyp.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pboaqxpg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2fttegmsp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrtedro.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysgrjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kouvnwkv.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbzwhod.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyyboeb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cssjzvzh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2grbpsuuf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiwnbig.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2taaretby.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgnrdtj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyivdref.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueembzbo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlkaqyh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxnqmpb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofspnxlg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bifshehe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2smsdjqpy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2easodpam.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2aofyzgwv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2izqypxix.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gesmrisp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpddimer.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mssukzpu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2juxirkoi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvpswqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgcehew.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnhzfnl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdthxjej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyxnxhr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwitnxm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2owkguyfx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjpzshu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbbqax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbakkrob.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2teobwqjr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2yryzjcyu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzznzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjopvyw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixrcpvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrdtssj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmxlhvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhadarw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbmpbkg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtgfvto.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzacva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzczwbu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkeresq.html


<!-- 参考信息 -->