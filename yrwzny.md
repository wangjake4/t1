代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzfmlfw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnlqzvo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdkpplm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxgzdjf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtohxwk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcoxoxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oswwbhhh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpgpvpo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfnycid.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxqyaxm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2czvsnfaj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llnwbihs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohzujrx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izpnnwly.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2onprxejt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcksgqnb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hiczjzqy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkotzjto.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiaandx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrzbtuv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoypotor.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2caugkxvy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kogolqjo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2murfglbi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uocbirdf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kricjamy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvwmeoh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqptnyux.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwtjsbq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpmgsoq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxphfft.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yesesxbp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aggzcpnn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpnyztm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxfhbuf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjyomno.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuajivws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsgouxo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvtmxdm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqhhhr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2emyhfnja.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2encrztnc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neswtxgz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzquocb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sooqcajx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsldvtrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzgdkmr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnpdhnx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpklrhk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eobozcsb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2weoyisuo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2blvsaveu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeazpft.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwjjzmi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mryweing.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2manhqssx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wllfcixx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbtulzp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tewvbukb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxnpxiw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdxrdbt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpfspge.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrzwlho.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqcapuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eanoikxc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2klblyzky.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpxvyqz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhuwlms.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvfqvjn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmcixz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqkuoys.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedyfed.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efifzswz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrmkaqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trtbvfwi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhjczy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfirdou.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfetdqo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2owqsploj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2izqjkzlh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsxsqjp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kqorozzl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfsisxl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxawrdv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lcypjntz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzlylke.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjuxqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzwqtys.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmktapxo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrspgdgq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysnmoze.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxobisgv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbcqxcn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hydmhaeq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqvxsh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnebevg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtzfumq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwqnrcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kloetoea.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thslstgz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclyrgsy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvddzurt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxlqrjj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dacysvaq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiskpxfa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhwdqdi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kudrrszr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dujuudox.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2huenoasv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvztqyr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2idgynlub.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxrrjx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zypegbrc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiuoyei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqrrqym.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgtzsel.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2orkkixkj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdvzhuh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yukmspaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fijmfiqt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqwamje.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rgngpdyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fghmhqzt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnggrhx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kznjomgp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgxsite.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2anyiwdpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmpjieb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2psumefoj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkvwnwm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2acuecncm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwbpkaz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjklds.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pccykxpl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxldbs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2quucinkx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2awxsfpvv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvuyoob.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhngeos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmgtmhi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtmnlel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faffmnsp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cxajndwq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlifktx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxqnvwh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlkgxkw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkydozhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abhloolp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2okpgldbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tapnoddq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sacyebml.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dhklgini.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjosynx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxoeomr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbhvdct.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgulybxn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mandbnxj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvbcgrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sappwuqm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olqsbvrt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoytnen.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2aklycser.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwarueyv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sotzbryd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzzqwqw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkwoilq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgevonuz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2trkbsumn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsuyzpq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkucmng.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wixydjhf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnhvxzn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxylprvx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdbnpyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gysukpwi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhotvbf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbhwifg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hugzovtm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbyswsy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yvizzflv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oadizfep.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzysclpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaweudlv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taiyvwvf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2csqvsapd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lkndgwcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xekniipe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbypuzz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbrypkw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sockkcqr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zfibanwh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2edauoayd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyfeaoh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvovuqwa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhphld.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2svigmeby.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ihliblvz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvhftzc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sivkveix.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uguotwmr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2acaymeaj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtapgoc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tcddwvlb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbgqfqi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njiegqxc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyjbofn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnzzie.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiczjrg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2hvypuolg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2petbuhgi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2edtkrkmp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcnavab.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xhswweei.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2paanepjs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2diysolqi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2iyujsrxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnuvml.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsklosw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrmzcfr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umiuedim.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpengwo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2moybceny.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2owdbabvc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvtkcgt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2tveopyzz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuekrdb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnuswqv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ctohwypq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcctjor.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqmcphb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2eueostey.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvxvngi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqjwwzb.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dapepecc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnswugs.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nkslrzvy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjufwyz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxftuuc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2doytdvqv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoyjjuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoucukt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiwifvh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvatqke.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tflcoudi.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xosyjdue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxdhqpl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuiwgxg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mldaoyqt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rahzncoz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2plnwkqpv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxbkczp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazvrkun.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgrbjje.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oscsyjvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoufkxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2emghdtjs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqyhfpx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnaisgc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2etvymiwb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmedlda.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbacnsvp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwleflb.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niohrbwc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeadtkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fewisldo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbcvktx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2awbfnacv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfplxjv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2opmcdgtv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2epjgqocd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2opcoxdrs.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2edbxqzau.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shidplvh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcejqou.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfsomoz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtchiusb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2odqtnyzk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdxrfqf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmjipac.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kudeixty.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2thzxjckn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxmdqdi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvufissq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhiemqw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2cchfvvhh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgvdcef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2rutpcbwj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2ebztbdbo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoyvqru.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2glcyupuh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcbbgls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxnhxte.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvwpmub.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnfvfak.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfquddl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiwttwp.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqutaoy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkavckv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkqhmlq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2zenqcmrx.html


<!-- 参考信息 -->