代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wngkcesr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmecbpv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdryrc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfngxqj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbdgwxq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxjbgxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhfekgo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deisyvcg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbozgcc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cusijryj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzyojbk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kttlirbc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vohaovws.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdljgfh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaapayu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2etfytnaa.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2azkxhfsd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2itwfswxh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpgyjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2knpcycgz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbcyzji.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqgfxnl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jedjksmb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bakasxsg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijclpft.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumsdgpt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfbjppz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqboolu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsrdnhb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgelfcrn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzyjnag.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtidkwa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2meanmsxn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpnnmwo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgpbmcs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnbknkw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmdboln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aogwhtui.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2feoigcdv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsixwtwo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gexjwipn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeoffvc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnirkvac.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemmhstu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfosbldd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcxjgqk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiyggdg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elkvjdtm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqhsbff.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmujne.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjalrt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mhousnht.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yosngaci.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfbinsl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pteplugl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2puloeuhu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2chgnreff.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpegolw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbflvjx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2puaekkyb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbmovwe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggivwntd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnachic.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlllkepn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifybqjpo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2woqagxos.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaucfxa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzecyxh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyimqsv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utuylsnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2unqiohgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmvumlp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjavysba.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiksato.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivzjjm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaztsdg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxnnjlj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2udprqsiu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uytadotv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhwpatx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lvazmsuh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cycswxjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqlqmwx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgnqotm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vqanawbr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwkpnuf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnaoafz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgcykkp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohudxyjb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnrisvk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfsbhfc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoukntl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcuwcsy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnujbavz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iueorknd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaiqjvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcsaldp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlgypbg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtboofl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchbjywo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeojdtsr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2raxrzohr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnheyhpf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihypngad.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2clekkcgr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wejlxaor.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kaijckgh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqbcqfo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcvqxhy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aosohlyu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlhkcbg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxkxah.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oydoztnz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2icikzbjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2syzimiis.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yynqieph.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgttmypj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzepfegs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2frbdjgaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wupcqauh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhscoit.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlpvovj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnvvbjd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexpscae.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxhsvgq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itdoacgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jswmyfsg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpibupi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2soarknlv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fquuqagy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exhnyibz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bhidnnqa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kerwxter.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfdklua.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcsekku.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywtxaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjtwarx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gantakze.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2obvaxlkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hngqqnak.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfexone.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbahmgy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxxlap.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhewmzm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slviatsu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofkunfl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnisomed.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhqxcck.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhwcbb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2norjzpui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gymvuquk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxbifhd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoxuzng.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcciozla.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzlwjzn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvemgta.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlscrsm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2slnouqvf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uilqchbv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyspiqhg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usxhwgqb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2erxcykyy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrjbath.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yactbmgg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrddcll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnyksdf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckndwkb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2meevmlwd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxalnuog.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clkygsuu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjzekbf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhbydim.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbwlyrp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tousuyph.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zelwxevu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmggdq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uexrwwlv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcvzqje.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djwzvdpu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpyzeos.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgxxde.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrhpijh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgoplxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxwrlba.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2iypbutxq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2htyvnhsw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzpcgyi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mtppnmsi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkfllec.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhlhxtn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbmkwap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwkemcl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zopsdeuf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtxiwrs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfatdai.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmrqedq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvqcgoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2khsaxrgc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhimkmo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcukuuc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkrwpbu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdxtmhm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblgybo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkprsdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzforwsn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lrshcbdv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2htfemhcy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkljufw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyknxlk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2olqfrizo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmyxijj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2asrrzxug.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwdvyde.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdhdhjd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdgudkl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xirhjosl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nexvsmob.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoubuvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpqyepw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdvpbki.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dadhkgqd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmaqyf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlhmldz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sanegdxs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqftzsv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2dihphvmg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbtteyp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pbngkfit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlstwce.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbdbhfk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdnrexw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcinozc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irzadjte.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2linvvygt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlsdtox.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aesakhda.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkavbivr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcnalhl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqxxkr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqjlhlh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2doosmzas.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kamhzepc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnccdqp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2furosjxc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdsaqcx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxkfdba.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjoiqaw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pielvqmp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwbphom.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xierxvai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzzevhv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjjelb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsglbai.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2khnthndp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2juhbguew.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnxqpfj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2frsihnaa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkskeqa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iktmhmzt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2urolvusq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiuvtcw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftcaix.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsgjjgu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsipwpk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2edsffcvu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjpvveo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmmbodk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2aebhoehn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyafayfd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2aldfitll.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxjdebp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnqyhju.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxgdzo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mleoyurm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynztiqov.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpbmlbx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkvbykh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttvjlqi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fehkfzpn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzumqzco.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmuxiyz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2quigpowt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2dktxcrgh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2vjadzech.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzabbnp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcphorlw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurilgg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2spsubkng.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgbsovb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdmqea.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrjpzgf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqejhfx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxspwmph.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2cymvpnju.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2etevzdog.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpcyzg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2twppnnnr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlzhtqg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qggrpmie.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2geihineq.html


<!-- 参考信息 -->