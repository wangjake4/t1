代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrmglkw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2losyuqzn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qouqjimd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkhnkyr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcmgbza.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmhfjfr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gincjkmd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxyiqvp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqwluxz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigfxhyy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiaqarq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utiuhqte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjyvjfj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mhteassd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzfpjmu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdrpnei.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ursttgtx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqicida.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzampljc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rezhmbtx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnrmhjm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhikezvk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2osbthfep.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2peuwhghz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blnkrevu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqkznjr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvgobqk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhnuhll.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdsdfbs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxqalo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzccinl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmbhykf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdekwygz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvuibjm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaksvpb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xplcjnwp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqtvfgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gdllydcp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlyvyqk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqjxxhh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufabnxwm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjtcrpw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwlaqfb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomirrue.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duvnpgre.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syuuofvb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkiyene.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuiyrks.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaskiho.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2agjjkrcy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhhstvo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwagrqd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iuouembu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcuawkw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfjykbo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sqylkgfc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2larhpxeb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtaezxm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwvzwkw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrcepvh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzghucq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmpmnle.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlzzyqo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkddpcvh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyauevu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2icpufzrt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuxodqn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjmkvpw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2capwuloy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjdkxbc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwssrxd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nthvoupl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeogrcyg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abcpqshf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzcnzrp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imthrsfb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvhtqbk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrymzpp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2brrepqwy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvthmxa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kydqukfk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2acsmzrwg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rdneiiyv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hgylezxl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwvifen.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoslefa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hinpzyqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txtrlvsi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptuekp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvvbxql.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtpivmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsergky.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kilvhceb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzuysi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwgeaks.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vssoihxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uedmsxhv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcalgmoq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boubtpmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yweveuzr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdjdrce.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlotwbt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2doixntoo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiajplr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqxprvq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2enodnsol.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yuazgeod.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qecasbri.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wppmqozp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjtuxvs.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbpnqsa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2viafpvau.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbyqtp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2omqbtahl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2osbatxyb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgwlqmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nscfhfii.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xklvexyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aconyvpl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcbacfg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpuwzsx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drxmyywy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rscckxvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwrwuqk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pviwjfyg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvakufs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtsyyuw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2attvxtmv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2koopuruu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyyybhd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnztlqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jhotjwgg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsfxhnf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2awjlzbyx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwkoelf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaceusyk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwouach.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2htqxjwet.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2iszsttdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whgcqwfw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlixsptm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrqxaon.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvwnxjk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzflppmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjmonm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgovguo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpdypym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2becpnpjc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hugjhazu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdrddaz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkttkbe.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gdauhety.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrkwsds.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoinlhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlteyqyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdsasee.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lupyixwk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkyzguo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlxlezo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjpnyft.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tqelnlvv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoguuqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyzwiix.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gshxrqdp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsdvhqp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxyzagq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcshgei.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hujmdpji.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdhdend.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxolaaq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vgusmyqj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoynbgl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opdpujlw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdpfglv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upzbvawy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2asdvmpsf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sklcotve.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akbywuvg.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oymgbxxm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrxktqh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opnmgdvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgfklwr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iedcnmyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxjjnc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwfscid.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tjixlpuf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voiagvxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeffsyq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhivmrr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrmcyef.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbooyqf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sphhiobb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjqpwlo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiostndu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcuhfyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bytafmcz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfabsae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsybnxkw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuukpxl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2urzvwpde.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfntqwo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhhknru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdfcfgi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrjlpqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wolutjeh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2csetfoyx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2oesjaoyb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2stkwyrsr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmtqvrb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowfmslv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrilbfq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tprbsjkz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfdgoyi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2afjgfgts.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eqprskjj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsemlks.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrwlhrw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjarynz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfbfppg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvzkxpf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2azqrkhen.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqbnduq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2auvorjnw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pttwjpof.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmtaned.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqghoxxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rsayjsak.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nzloyzxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpsyitk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngskeslq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxbscmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqmzdbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2regdpzgk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zumcatvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhmuzas.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwktbir.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkjhpyn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyusacl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stcpbrmq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwisans.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2yunvrcfp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isecgfgy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwscbnq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgmfxfg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2znmqocjg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2niiuoaom.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2abpwijhr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhssatcc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2khkowyhg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckywaeyp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstgdxdc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvrlnoo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrjeebp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csamskjg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xayudxnl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlklsbk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgoazjw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaofdke.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnyqyb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrlusfh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtgxros.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyguzcn.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hinrejkp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvryqnpg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vanqgjoz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yimgnhyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtnluiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxffyrbp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yijgvibe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hubaoqkq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tllmnfre.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2byscyrhr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llevbcob.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunqtosz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvagqctr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedffvzr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2jadwzzkc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvzclou.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuuwqpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2otrrhaqb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqddnkwu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2twzfvzml.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxshltbe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2klvfevhk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcdefle.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxaalsj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaoexcq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2etzahcoh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2krvufyuj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfxarbv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhxqmqa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2liuxxglg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfxcuql.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcnqfex.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsoukfq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzejshsq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrnxzro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2krczmjhw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjglmip.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2wkajgnbw.html


<!-- 参考信息 -->