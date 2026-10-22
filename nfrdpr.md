代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdpyyfm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uckfsuka.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmrphet.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugamryc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atttclhk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyghyiz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qarwbshj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwzmnzz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtlkgg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvppkrl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvknklck.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbibjqvb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjlmiqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmabwks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hskyladv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zytpkujk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujswjdtj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsfeiuo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2woqcctlj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfpdeaw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zszsrbjo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkbyeed.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzetamd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyqcwfn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzliecd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkiadhw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2adggulwt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2astuxhui.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2togpcaca.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvrsvlw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svbuzbgm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqztknef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktcnwkv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mregdsfy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlzlbxt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vrerfwes.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrshkhw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fomrfadl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkbclmy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oysqfvwn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhexhzvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamrkzk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyayyzxj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbomxns.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjmlbyg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vifbqtns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkuboro.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntutarv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpmdpgb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vihoswtk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yespahng.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeiytrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuxgaya.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2omzdpmzt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrabgtei.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlnhjhn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpteosge.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bydzclrq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcjioyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2excdxbcy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfcwryt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszsgqc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcoppym.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsgobcy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ossllujd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szgqncxf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhlbkxv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhejrcfw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2isvyaykv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbecqv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvacbt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2swobwofi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lilrzood.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssokgtpy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jplqfpis.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blinaolh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpvnguy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedzkftp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgfgnce.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuksyox.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxslymt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvzjxsk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxwgypx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sdibcyse.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eyftmfik.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qydevvyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcsncsl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vkllqucd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcmzov.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lholniiv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2njchkdka.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rglzppkn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpjvala.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xllxcjhd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtilooq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2blrlsnft.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tketpoes.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgesduy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpajixs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2secysrxf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtequzdc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzrhqau.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqplckg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osatthff.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gahumobo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqoqdyv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnahlmdp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sveknjkk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrkzwkw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuujhfw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwfohm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvgammf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjflubp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdzjzwi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpuxcmp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaofjyv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bftgccmh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yhexxvqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kozbkfpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvapfghp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqetdbmq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzrwrdr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfucflgo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2muaynzhr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeexkvmd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuxchvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fdraqgyo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmvjhrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2weggpgji.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqehdee.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkekvdzj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2megbjgzf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqefbid.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvbbizl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxgkqhc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bgokkidz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaljhtkf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqnsknz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cghrgqmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2trbehofl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pstapbid.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jblbvlfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2famhjjfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbmqyuf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjsogy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiakwgn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uablogly.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkrajat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsecvctf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvrdulj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqycdllc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafkuorz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ninxzxur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tosjhjvb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfddcxhu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2emdlhmwu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjygoytc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdypejye.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxljkkx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tengeylq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailtryyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfupxed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grgsqjic.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlmafvz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2guytftpn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkabmyo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzazevkp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2igrgvlfy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxidapna.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xojmfbtn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnvgsxp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgashfne.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhgzsbv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijediwjg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtrvzhv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rysnzacz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mimwruet.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfilcvbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjazmboc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2glxgcmpf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrtlwlp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lenxjaal.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdihlfl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmgkcph.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfohhnx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxvekux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koqrreeu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkipilk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgcmlux.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mdacweog.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cukawciu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2melozrtq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtmvrno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rckfapqb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpxmfwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qdberxzh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtviksca.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnnhdlg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izlaypha.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2woyirfse.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ssajcfxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaigjfb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ispdnktu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwwnkic.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfwhifr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gibmefsl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2datrspca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpgkzbd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mymhjcnn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijamqe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyzvwkv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhudrwy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkeehjp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyewyut.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhpouax.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mntpxnjy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwkpxpz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mchxcfks.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2drwoxcyc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhbnahk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xicmrtmq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ervqqooc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvqtnyk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhidgbi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2klpofpkz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvrxha.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgbcpl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzmxkwx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjfbauk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2locwbpov.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfhynew.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jyewpret.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2etmgjgfn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjszpry.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnvepkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaolkqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaesyscl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rguixoeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycotcobg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2znulglre.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qswcaugg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmqihhl.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfuceyf.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvjwlip.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgqclql.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvudbqo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2evvpkeal.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtmsfub.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrudqn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjdrdvp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlxhwyh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtezgny.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbuxvhv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oklrcjuw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zftvujow.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqexmdn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfveqjva.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2svhbzclx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwrfxvd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmgvpjh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iroyaent.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jibkafjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brikoqmm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgkwhs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdorypl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsahdiw.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoaihcj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgneyqb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buftikzu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgljcjo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkhxiaz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmphyqug.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdmjnkr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvozznlt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wutwbmud.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rkafntfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljixdlvc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2usqullcp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwlhgaq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2enxmhwjq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwilbga.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvikaoo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlaiees.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaojnfx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzxvtda.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2soxviulk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrpuend.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnhscvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbmszf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpozmwe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2tacislft.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpbevch.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2reexyhpa.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxhggkn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabvbvni.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgtthno.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkkvbjp.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2frfqfmjx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkifdekq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijgocao.html


<!-- 参考信息 -->