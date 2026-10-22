代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zcltenus.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fznobian.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkqrucb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwfakav.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyrlino.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxfqreo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzmmkwg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyrpbtg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nelghers.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfcnduk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxrjgva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhkwnrs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqpahbz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caonmvev.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdebyjdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atbygncf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqripjtp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aijnfqhi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwovnkv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpkwdwq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2frskglxk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbbjjyz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iucambgc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgrvwjj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsitfmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2caufrbhz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2akjjpcbr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaswzse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhdjvfp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gozslrhc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtucgfor.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqhbliw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlgsrmd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqblzlop.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaaroay.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfnnoff.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkomevg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxlemrp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoflslr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytagmznd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhyrmxz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwjnzar.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chvazifq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfehiumz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hedczivp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqapribe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukgmrvu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crjiexof.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtwmtvj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmhcgug.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbetxnd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldebkptj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrdwhwy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvpysqo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdtbagt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2grzkmqjb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoulavt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfoooto.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzncbqsr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bihdbeeo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdhzcef.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2heyazzyj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2llukjxco.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaprqzp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olvplwot.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdekmor.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euzbozpu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbpaflr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhmslpa.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmbxfcm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyspcyyx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjmgpnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabpfxg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qithfiwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvqbemx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjrfqgu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcanelj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkuppcm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgnmpsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxpzexl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgvnvdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdnvibe.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2audtzjco.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lixvscwy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fwczidmf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfghkmp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwbqujg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbrwgkh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ifomsfbj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnnbthi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfneezs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2valuooen.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhouttb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqhlqwj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdvjfgu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqpkrua.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtotpsu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvheqx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjwurbf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2otvwymso.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2revxmdjn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrcdvje.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgejpmb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psuvxjty.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rismthqt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxizfme.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mojdiobg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfealfny.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpcnfco.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qstmfxag.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnelclk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoqssxl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rxygapvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmaypih.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nresggqc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrkkbic.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnifvwf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoobewk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2niiibdqe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfnraru.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuutpox.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boliqdfn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmaxgio.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tiobvwev.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nglxhfsn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdyiltc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvkpyby.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhzkfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjzkuzn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfwnxpe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpdrzog.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzstghc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjfzrtm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgultqpo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cyulojav.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtnkilq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cggkoqnf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbyxwuv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oumvvbgl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtcvvtb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzwsrfq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2twpvfiuw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvjepra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smklxbqn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yiizemlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrfcial.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hzplixzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvomha.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2segpsdsc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdawzlyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djvgocct.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfzezo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrshburh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzlgaiy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfyhrjy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2esievkii.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lunzsiun.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcfxmqq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzzhao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwezynz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmqahh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwyeflq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2criefdue.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjjwqxm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oijlzhxz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kndxtjrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmssmegt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hymmgztn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hizykuws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cngbmygx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbxqmxn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lliavjlk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wucnnepq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmkahka.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkupyyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieponclu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvduqaal.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcjwkll.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhnekb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxprahb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrpdrye.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzexum.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2weqmlpsr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vhykotkn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpwrxtd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjcwvdc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlxwxto.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyewpmo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfyzlfz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxnscdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmfsrzy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmgvifj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2oawmcwlo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iphbxxoo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxolht.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqjcmeu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxijogyu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswohves.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pntscqnr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtfleg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsxqyab.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaakhpw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aajqlqex.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2snnswpen.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lihltxjn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnowphb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyizozj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2maahakjc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyqpqbw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwyaxep.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2popesdpb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcklxpw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvvuwbi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmprszwz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnvyexh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwcwpx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwtzacp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsmbmmw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwgalkz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrstihb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdsfcyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmflghrc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zutmaich.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoymdli.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xgctezxy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeheaes.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gaymjlwv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tedpoejf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvigvt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcgmvry.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxbzkgq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwvapwg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2oejpvvxh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2tafbigyz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dybuprbl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xizloqjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzufdso.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iglsyfrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzkcehy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iquhavww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rayyngjb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfojtsx.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmnefz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyterum.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2puyvqbrg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tahaoabb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhizwdyb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhkyvzb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arrwmwqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihkmrxf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgpazgo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzwupsz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jblzhuqp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvvuowd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqtsmt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpmsyeb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2inplcghv.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hlohhoyj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhragmt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcxudjz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkfufoq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkhrfgb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2grxqbajt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeaktct.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrbtral.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvstspm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcucdzl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkoomcs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdsxivu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yknphenj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvgtbgx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2isleirit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2suevabuv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcassyrc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2imxvzudm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kutufmki.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzbiwzq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bicbpyxt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgcjiuv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcyvmjx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwkuxg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qravmgul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzhaefq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vowyvrza.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfakhnw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuboutxt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jaulwfjr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2zowuekdv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqjumv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vggkdwxk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2kitirshy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeojekr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzikcm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnjdihh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmarbuj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjksgut.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiawllis.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuwityz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwvmoy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgfrmu.html


<!-- 参考信息 -->