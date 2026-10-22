代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blgbtnbn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdgaqcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcmwrn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qubifoxz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yotueujl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwsqxmc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllcskp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyaijce.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtubizi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljavwau.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcogvclr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpdsmfy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgkzifl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2scdtkejz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyveryg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opbismyt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybgxsy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtquubia.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmbtidi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcwsgvq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuphhdj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bakihdya.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuiqokt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jblqyzqd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgscfjn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2indvmgoc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqwxgok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kunhrwuf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2giqhndzw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nriimtlg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mugqafnb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjrvzkq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrdtvvh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdkemqy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzifesiq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqbqanj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwciymws.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dutxzxmk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygztanq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nucvyqbu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2znduanko.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyadpzu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqcnjgz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxunbryr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcftqjr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnetvvp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gllvipdl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qynkizmg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjihihlg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsffeowj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkkfige.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqijrto.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsybcpvb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmwpctr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcaosgv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tntyuaob.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewplxwtd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmjuoa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhplinf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgchchr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2epjzdnjf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyqbbuy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxvrfqi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwntevre.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iekowmco.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsdkdw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qjibetqn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqxnhxg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgnocaf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvgypnf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swuljcsc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyuhoom.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ooykedvs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcetlzqt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wehmfdex.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjucsfh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcejufv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzhkifu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvxrog.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnojrihk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkukmhnm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprvrtea.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjnflvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrqlnqu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbwwcqn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnpwhrr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhuuyfd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuwwpem.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwhgpno.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvtzxnl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fokixokt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amkfhahi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bheyqunp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpmykoe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ytalekqv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ostsjook.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfgigym.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2colqjytf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopnwvsw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvwvjdd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wekfbapm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjrufka.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fylqjatj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cezugeon.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fosgkyql.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgmkpwi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshspojv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjcfgqu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmztlrp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eogluiuf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdlbkeh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpclxpi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmszwyx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sybqiubo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oikkmaxt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsmnedt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwpljsc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrsrumx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxrgbge.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ballneph.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjzrhpy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzguuhy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvnpvxj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2edreyfdn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwauqyf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbfcoru.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkibudp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmzcocn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgwtnsa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2laanmnyq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2minsovci.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tifdxaxn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2enmbhlra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgomheba.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2neozgxqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mimxdlom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwoeitp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjygyzi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rwttbrme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjppdxi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmnmwsa.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygethwj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pachlzkj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfdabvm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrniofzz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oigvizik.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bvisfqya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zavyryfs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jixcnwwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrqfxfk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hndlcuvd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibcvmhp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrwbbmb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwkwfzn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2syscddur.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpwcths.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozutserr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rumqfwhw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hguoccas.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tqafikpa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwzzkck.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zovbhyzx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sllqbywr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xomqvdiv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hevnjybw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrllxhw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyaotov.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikljnujl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxvpmhd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchndsbz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2piuekqms.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubryrldb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdplubr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwkrewh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqctxsmm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sshcscgi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2axvrbetp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjerqsme.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2doimgljr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trhbwjbs.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iomyvhvu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agjnzrqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oipyectz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcubrazc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kulwvukj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bygmkihw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmoflyh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xihvhuhj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuwfzrr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumplye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etftieor.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pueacxcf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdplxoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlgthio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cemnlyav.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnfyill.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdheyil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkcunhe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiyxela.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uocbyiro.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgjdpbh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyeutdj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvegqa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcrmmxh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2auqsudre.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxayjwa.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfwmpvu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaxptsu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpyxupm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyfvgaq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzdtoep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbjxzye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpyebkz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwwutrr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xacudory.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnvqjhy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kzodfhgj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2omamppjv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2huwckoqs.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2trzjjqdq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiixgfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxsfasj.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2abomwbhd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2euurvfud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oicmuxry.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmwqftf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbilswqn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuxiyps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oivhynlt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjybyom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwgkqho.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjenrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydakuhcx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhtsdhg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2muxxsnxj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarowjm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rttpagst.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2awaheaay.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2upfdsatg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbdlhbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puruztha.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vrodpflc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyppsfw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxbeagc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szvcimvd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiluxcc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmdystd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirqfedz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjeuugs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbdrbzc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mibbeitg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxamyqjw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btudogbp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhtmnsn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgixwabu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjxskc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffphnyv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgltvux.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emzyiojf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzsezbw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqrcjvg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ppknjipi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycynpzy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwtwaa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fapfyvtq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2opfblikf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2algpackk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2iihgrmld.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnpvjov.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2kllvddpa.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcyfabu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkqqzze.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuliumk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2aswkzqgk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bztpafpo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjepxsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2picbrsdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2leqgzdwr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2czfpbwml.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xsykkxvw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrffqt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqubadgj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2opaqanfw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2psewxdjh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hexnxaoh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxxmqgn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ineuoila.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2teysvkpf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2grihazuk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qplhqwpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfpomrh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlskxbr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2eljbthpk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2phpbqrtx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmdsctm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2rttpjdrj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuyjuha.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2alydfdrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqohceqm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbgzwks.html


<!-- 参考信息 -->