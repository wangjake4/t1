代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfyfyow.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbmjryw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2snijthru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qizbjgbj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqdcjvq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nxktpslp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rptsypyk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnbygag.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2poznssdk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoffnuf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czjkisxb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2egeisfkz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dikrreod.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fizlksjf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwxbpvy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrfcmwh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndljbbnv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vczfsjwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwtktzy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvrjwox.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yehleklf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2caaffhqa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoepnqf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jssacjrx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dicxdayo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwbcicu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyodxzhn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvegcuw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntogiakr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tmllvuig.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oniravyl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnvtrtj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcevvzh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieveabzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnxcnfo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2retiqrlt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gynlbtlh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwyietz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfynxtu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmkzbrd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbsckav.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwtgzqy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmkesib.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzevajma.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaddgil.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gljhpzcm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imqpacgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bchihlxu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcudadl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjenvrnj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2llohlzcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrmvkop.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roqjodsc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwbjyun.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjzwvje.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unynujcs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2joaucbnv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utszubvg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfasszid.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xraxfxeb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tfowfrbo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thinowrj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnexzmk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuveoyis.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvjgfog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnvwtlx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnbafui.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gumelvju.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvocilun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wecmcxoj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2puidirfx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zafsodqj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvsdqdn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqtiaub.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhxfteg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpxzrxt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uayyxvcy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mxibndkn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjizbha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqfxdhq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcirnwg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhsxvds.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmqauld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjvpycl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlihpzg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcblfcjf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hukamkfj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiujgju.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqrjlwy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjpmzhi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcgifmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoedaimm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2enlqmmwz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrcsvvv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzlysnq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2leowambp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnvkvxa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvuhtbg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xorrnnqf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkdhegv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgqdrhr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwjhzgr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaueseds.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2abbezxiy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kfatwold.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yomjuvle.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pucwmdpz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqfuyua.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2exdpvezw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrgbgws.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gucuoeft.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2luooqwfb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvojwonb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hsntxljh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbingsr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ramlbdcm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lcghqxhj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzzmded.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjauqhzp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcndnrd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2twxyofze.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyuhyds.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxrrmuw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jorzvhyk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrnhcft.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pntmihdk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtugohl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oksaubzj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2unxgbgna.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kayvvvib.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ergdqgqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tposlxui.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aresufol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hznoybao.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhpwwuc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvksudxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gplakxyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhcjltz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhglfwhu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqhcizs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2litdqddb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjrhsaj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwlkinr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgmoaln.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyievzaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddailtcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imcbxgmz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihejkrlx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glmxowyp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwwksch.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxtkykv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsrtqaa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eycvpzqv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2icuffgyt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzneuywv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2shuokmcl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjwqhn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcvonfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbrmzsl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqedacgf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2duiucrqa.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zahxzfpu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzkmfj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aygngall.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaexwsxc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neqfyocz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcstnsmh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gucqqqnr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcmxumk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rorviouw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrohyvd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjpjtrm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmclyku.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeqftbz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnvzvky.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxcnsvw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmkjujs.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2truvqsme.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onfdiydz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeamgky.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuohhyr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2decmktti.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mtheazhs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrizabw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjaldie.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqinrkl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtnzbq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfaxfhq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2klujlalf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2saabrnza.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2upatjdis.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfndqawp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuszxgv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxxexgu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxiznad.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxbvhgs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahidxpao.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zjngwnma.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cugohoku.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbdqhge.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ucavsmma.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2grhifvff.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscrptxt.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2braudkvn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ijolzjyr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqtetss.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuxpdbv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ceturgjb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2owvzzile.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lohebchd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2olslefhi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwurwrzv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhttyol.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagpcfmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjqjvie.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrxzkrb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2figauuro.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqbpdmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqfxrwx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnjyzak.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2viidythq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrwgvko.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnrsutq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bevllwzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyowsrsi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbnllkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxbnln.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkkbwyz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2diljaawo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjsqtjp.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxqetmy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvzdjsl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2thzilomv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsjjjbx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2foehbguz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmxwhom.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yblwjviv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fboctiej.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyqxeul.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqbccjf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoobabr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmnbai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smuhbqib.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2seveahqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnbgzks.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oknvdfkk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovlolqt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhxnbka.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmthfpts.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2srgbpnxa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osecwbhp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2laxpvfbp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uufqpqts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvqbkkd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbprxesv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kngabgzd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmncoigc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvryghy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvmtqru.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2prtqlwbh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rryqgldl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwmobee.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuyfkvr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uchxikmk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mskdnmle.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vonjirsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxxugv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lquuhadu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pppwdebw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avrzuqzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2inumtqld.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjyzlax.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2glhdogkc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkgrspe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrpuuvq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnaxjrp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjgvsmb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvprsax.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2engzkyfm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2odnazmiz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vokwtxkh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zazuuwzq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2bystowqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttldsgqw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwulbvm.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqutewj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2esyvdyyr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrddhqd.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2evlllblv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxugylbw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2edoqhlfi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoecsir.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2beceyqyw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyguwdg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcpstsh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2barqjwre.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzhbhks.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzvvovq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkumazde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwxhnva.html


<!-- 参考信息 -->