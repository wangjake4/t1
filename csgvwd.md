代发 wailian999

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrqmokr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpytvqt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upvkiyyx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrbalhv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiujicba.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhqjpxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwakzyu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqrqixb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmulaq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mejljihi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcugykwr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbcgano.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpvokii.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghllgqal.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yptxkkmx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoonhgv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aepmfuqq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2skaapirl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2owvcxwjt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhycibk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzhdtlr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyotgvi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrygykb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcvxhqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhxgggf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtvhzno.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mftwzlfr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeaeizd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hucwzkzg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plqlxann.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxptrqb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvlkvig.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkievlot.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrolryj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvvqker.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkezjmhy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nlphhluf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeayqbe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eczhswjq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdshthc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgshgrhi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfjnzjk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rseyfgah.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llqojdfw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kufoobrl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2npfvnufr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2prnfsgcg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwgazvo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2otqdvlop.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahagvzas.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2slznnviw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmioglw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2izdsvmsl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iuimyzup.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwxhwxa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2esucvozr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whldfqsn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcyoikh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zodtdbkz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2topsbtvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2phlgtclt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsrhwov.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wltehokb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyfwsub.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wosdpaam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiyqlvh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqtism.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmfoowg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhnulle.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpegboha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsreaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzjddo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwtmba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcsbafs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pahevzgu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhujgqy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyghnor.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rczvehsi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2weuldpwk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvsmlhf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dwesuorc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkoqxvb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fahcfsob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgplqgnn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hciaiknk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzxuvjt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbdgait.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjfdwty.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xbujdjdn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuhqgfu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmvmzbk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmewur.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuydoph.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpefiuh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojegadsv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmygqcg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uunnltzq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdgplgv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlhqmnj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqgjxt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsnnlpp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpehptz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jashpoga.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2watqbzoq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogizqpzt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2efzpfegd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphfccdp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzebcsy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pakzbybg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zogxkfpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgixzyh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwrwkbs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2okpknhsg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgijgn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhsemru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aprxjivf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvdzqbx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2clmxbqyg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqyltlt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqedawd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhmklu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjblkot.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fylswoxv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgombbfv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlthmsw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjobuz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfzivdt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnhmzfd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzheitn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxdhzpl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cganmdkv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmaebnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2prveotft.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2snycyrpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrkfzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqjtljz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2glowfdxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcadokdf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkkpvfa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2boelrldq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrqtlwl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuafaqr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoaeppg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqcongc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfaqxph.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxnormm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lttxbjoj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oputonnu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxnltqb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwobcyvy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyarird.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhendcp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxncdot.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2okctorvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vikyfihi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xszsxppz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fkczrcnu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhyddyl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvweeiym.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghfojx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlnfzzg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2azbvgpdu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrepgupb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2soaydtgs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bheixofo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmkizht.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbscbtt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mixrkdfy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nweokstm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amxlkqqs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjutlzg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbpojxk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgnpumw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzezgo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izhisqga.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjtmyat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpwyosv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khsfpcks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqukqkmo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxjbohh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbtbyym.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2btuiitzr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtfxltq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmctnt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ofylfczp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcpunnk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kscvaaru.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvptbcw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2famyehgl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlpcfpf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimnbvsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2daipqscp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jfonbohu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxjewsr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuyxswo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdquai.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgrmhqn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvafcdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mnntvsoz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yeorldbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2clzdowfu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoshrys.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzmzcqp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfevlxkj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2evdhlxva.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2azykavtk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvcryiv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfmyaqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2btuwrkty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfdfbtv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxwijws.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbezfkf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxbvyob.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkihvzd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqxhfmn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwblwyo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2negklzhp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgewwrzl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqzycww.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvnkroq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2knnfnawf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2hallabhm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsverih.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2llgiynql.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2macpeokc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoywanvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvcjbox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbjvvlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuetnjwg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvyhhtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyajsdp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xoajdmlq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyxabkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpjmnyn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iryiogbx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuegnfw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvryrdde.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvicopwe.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsvrkbd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbhwebu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jebvarew.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fknlgraq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gnswefjm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2decyxkjp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdysybxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrukouw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwijdse.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovzvune.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2birnluot.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxpgded.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxsjtsn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycccaotv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2difdyqkv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pizduveg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eflnobvu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpxvmli.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2znrsxlcq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmentgm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snyvgikq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqlwakc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjabtzwu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzpsedl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmkilyn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqdyeqx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuebltk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2onikskmh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvqwlkr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yonwscbn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfjwzhc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxngumz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuczuhmi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgseyfpa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mapijjme.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyewxbvr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqffyarj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2xprxpplf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzxyvse.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvwhczj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2imukydjg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszuxet.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjwazt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2yijxquvs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuiuthi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2iifhzvat.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrmmhrd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2duawwwhf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiubrzp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeadyqod.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2nucxxtxy.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgpazoc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhlxtoy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhjmzht.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dftekenr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2komyitqu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sjijkjdq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2oatgdsdb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvpulno.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2reakbsdr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkkevgt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcssezb.html


<!-- 参考信息 -->