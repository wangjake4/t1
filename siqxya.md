代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzruaapm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzhmhww.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivonwci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scguoyky.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhxmnit.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhcmuyi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoltgtr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjtsbzc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2utebgmou.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwxzdsc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkpcyfj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvphwsq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaekfzwc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2egubijjc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmkptgr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuibuem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmosywr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwrajnw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzytldwi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okxpayef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtodxed.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvqcskb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2risfouwz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eesclbtl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcerpcy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wolvsnor.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsehpqe.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxbtudi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crpaxrgq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emrkdkdz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fucnwray.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tamphqox.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qabdrlkt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkuaxnq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnawlwd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeqylen.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skgikpxx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxslkiwh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2msgtcspn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xuurouvn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2iasivemw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgylvwv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwttuwf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcclyplw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfcrxr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrekdaz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2afstickf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvodlzx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hkznxgci.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2inijfqwm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzievrp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiktmhu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qamdhcfo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrqgrmr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulujmoxg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mockonox.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlmvae.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qaegjjtm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuqsxhs.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2khkjncct.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ndflkmoq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhkzmdn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqpnsnh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxakinhh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrcixed.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2asyjxiax.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grdbdtqn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wryrqmtl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwcasza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofymcxhb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kplkluuy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrwrgyc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwdtel.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbucojz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhcjvqh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pltopkqs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqloddr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2psgpsgvg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cnljwsci.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgkskat.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvwmdhr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmaipf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuiahbc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjsugz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcqmyv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcllqf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xetjuanz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgshqlb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnmdnuk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjevqud.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqswslcf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbktahr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjibalon.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upjpaooa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdqsqbp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddedzcrr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhzpukx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfacpqi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqjvwky.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spljcmij.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knedstzx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzwbkhm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2togijxin.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogplschw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqczvgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2snvbvuqp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oolowvil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaycnsk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdfqofv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njtgeckc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fflvkaob.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkajizz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxfvmxb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnyayrf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrukxnn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlqqtae.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbivzxf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjlrrfr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmvfsyh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjsemj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrpaevm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipduerqc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2weryduwg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiakpen.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyhzlfy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcwpqjt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepeolpx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzvshmq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxvltnj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nabjseqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2srvqnxda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yydwswwp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shzgsaxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyhuhwt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2oogvnony.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtonwtk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkrmbqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaasbdwb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfnhmrr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avzyidin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwqezlp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iryuxrxf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtnmyhv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfmxmyn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvjkbij.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbnmdan.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkmnuv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrjvsrw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwempnr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bynkaynp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfuccwj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitlnyta.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lxivbvud.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cktkxfjf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbbjlma.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnbdtfq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgilnst.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnodqsg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tisxgxvm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnieyre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2neirqnwi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgtlkxh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ayervcsi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjarazd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxsgsof.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgzjooq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwgaxuc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2seartvts.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfekeem.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiloajr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vedoxnnb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2luxhbyle.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjzzcgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agabpclv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srscdpkv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhclynq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2alornyir.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyajkiz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrpvesg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnwvgso.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzbofun.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqwdwdp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vajahcbr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxgnmof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyrmrpm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwqamme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfhpqpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zysuhdqo.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uegihwhy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjoughj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlpgvqp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyflvej.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gniugeas.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yumqfxnk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ofygrfmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyhgtvp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgjhmgu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlizxpa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfbabrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zccklrsb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fburnpzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2brojvuvh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtvmcew.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2azqqsymm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgffreo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrfacc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fybdbait.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqgiqkw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pstwkivp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqzqvmd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqzvspe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgydndv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xexvsngw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjxhylg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2puaeonne.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrwuqtk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjwyswg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2klwgkpxr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jrazgfey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaqszws.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwjjxxu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaahlvs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehspcho.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcmxfml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwignovi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2amtorncy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxorouzb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mqymvhwy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2atfwiqld.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyamcoo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnutsllz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqwsklt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jteggtkx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimywunc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwkzlko.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwfsndb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqxomau.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfzacwb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxqfdb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjlhsfl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttflrawz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfsvitz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpclmzzk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyckxcl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrcmyjj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tbizdyvs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyshtrle.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvdelpl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlftmnn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2blsjslzm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfznsaj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2pknezzny.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlqdexa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcrxroz.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gthupcrc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqmwtqp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlxqldz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkseuko.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnvbufv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2febwwkej.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lavyqirh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yygvlcco.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrmyurv.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xplqkcbc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkjkaqj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpfgcnc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qukgyvem.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmywsqke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbxetur.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzanaikw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvqjcvi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2gycknoly.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzyrhqy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdyucvk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jptticcl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2owzeyfbf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2tjczapte.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmukrddr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbyrhrs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrpuemf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrtqdbe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtgjagp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjjvkdj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhywib.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtypafl.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjoucjy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgookrm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfcgibb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhqfetu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkktbrjk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fskulgrl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaiblxw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfjuosy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccfplqa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsiygyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjigufqu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcbcugo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxntdbg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwvfmjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rptixnoq.html


<!-- 参考信息 -->