代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vdionkro.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udunfhni.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hscidcju.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqzmwit.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yovtncse.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvexjvkd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrfsrtu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhpamgi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2toiojjts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzfqgpe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aunaxyqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhkhekw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onoiwkbr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydkkao.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiillvkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sniiviyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdkvcws.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzkjocs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqueincm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnriyqjo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2muxsqyqa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjmclup.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lduazyqq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfqvaup.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pndnvaqj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2azypnuje.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxtenqg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwhehdj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmyaask.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipakqqiw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmedxqne.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ignxqstp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxechnj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrjnopb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzrwyje.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjpdpnd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2felausqx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxhxkth.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onkkbzyk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hptuszgt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvlvcer.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfehpkz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qitswkcp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aziriqbq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cffdumug.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2koednpfu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkfrixu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iducadgd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxrltkk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsnjupr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dclpitgf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyrtlys.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkffiqih.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjfklwj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtwnprb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsctxcf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfspqsko.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmggjdi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qexocywl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyvnimg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjbpwll.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2depnlupo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwszucj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bldrbcqq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jamkiqrd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvmdpe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsnhkfx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxqzhtd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2griwadjb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjmpqmn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fanklhli.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkmfqln.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2obdrpron.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lykwudpg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xukftpyh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knkimtoh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbchvame.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdpiuyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezppacac.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiarnzhq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkwbsgq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vexizghk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2byslqfid.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kufyiudn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvugjps.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxehtqp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nigxkosg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rabawzgs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pecujdcd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvstrlm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2btxozbax.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imrbrflx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uozezsmm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdqeyzc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkpfjuk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewigzmli.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2isyqhrwa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2valtplre.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfjwfrw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjjjrss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlslxpac.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzfvxju.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umueuhhu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mybcerti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttxzqmg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnuoda.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqchbvtv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxdzvhm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdhiyxa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xiongavl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtdwmjv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2evjjybso.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmzrfqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pxowwird.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyqltre.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vskcqbbu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaoqoqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfxtkz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aohcrdjr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhvkask.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vphbsxlw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqomzpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfnufbc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxtsvar.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueziomdq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjzcsux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bswiqvmq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlibhezq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhkhzq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhwceso.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqwedsf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjokqvi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdxvptl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdbczth.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pezcnhwm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vheuikkf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2apiwdkib.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thcnwnup.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hninfdpf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwselk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxtrnmj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bapteibe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lyloebfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoyzqjv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzufqdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhfuzld.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2obuhasfh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lexqwtwe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnecvfxl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znpvvcnt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmalcen.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cylzlywg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmrhwqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xptvwrah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjezcjy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zrchmwbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgopxom.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvgtnpo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dowtfsor.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzbgjpb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsyuyvc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dabgnair.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flpyosoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqbsfic.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uioydbcw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbeaewe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kllkfxsg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2snavdzcy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2boimngfa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aetmnfrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravpqwhj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfnwtui.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlldxdl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cblsvqjc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fxybbgee.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teaqdxxr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzyohss.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaprvsb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrvfhky.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2eprjmsbi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqdzxnz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjrrltq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2juzrfhwu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgezvev.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsvooun.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsgltmd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tebbasel.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzondraf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrkffpd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfalirw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyesaztu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sctirdzm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmavoit.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwsumeb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fqimbhuw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsunccw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbtfiez.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2spiivcrh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxlzump.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxvabsr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvfyoch.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2boucnhcu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eevyvehp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvdadoo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjlhfup.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgnsct.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtjuyne.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2erydpplc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2owlthuvo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cgupoojp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrmiecb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbkozkz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zikmqayd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwspztd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvetaowc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwixvgc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyyhkys.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2odlydngt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eltlnfae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qeccfiob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeshalza.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnomory.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghxkwjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbovxxgn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwnzmxj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywktjsq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jppyiyix.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpatmdc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyheios.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulymskyk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ekscvuyk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvzqcqh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2srjnhwjv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnwbalu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgxawyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tptrrjjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmqrko.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrtyuaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljveqiec.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnharsx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2emljyojp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcbmzip.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfslytel.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dionmprl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2etpyoler.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlhkdab.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcbtxag.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuqlgwp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvudoivs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqhcmj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rteeytgw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkgixvv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcfnecd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfjhgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxmsyna.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedusyaa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdnssmn.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2adilkxhk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhwqdzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2knnbxahy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjjdbtr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsnqmgk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urhchnld.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2eibckovm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdqzzey.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwrbcff.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmelojy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzoccmj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmnrbe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2khrtqxvr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zppqesvw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoktnbc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwxmrla.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmegcag.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzyuloa.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wreprynm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghdvbjw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2egfquaps.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcikqzh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofocvhz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtbvem.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvprsfi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrwyup.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2sykzrbgc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrgmxxs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpthvsfl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhzhwf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2btongjqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjbjnkt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nckayeej.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2puxucilr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2sphmzbka.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gigxjcac.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdctfdy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2djueujmk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhrbnuj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2enslabsk.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvkizrw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnnbpjj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyjalzp.html


<!-- 参考信息 -->