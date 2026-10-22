代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbopwbz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjntylmk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfanpud.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmhmyeu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaxbqzg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2orqwdtpb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsknxrz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owruzxau.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdnhlhh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zayfknfn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2khhpjrgb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snnprgbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbrigkd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izwnezlq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2toxhggij.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbrqmtj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2siuqdjnf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmcdhns.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rryeysja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbqmpy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2spacwjgc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdexcal.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqwvkgt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gcffliym.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvauiegd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnmfbez.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyauwcjb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmiwtu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smuvcdck.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxbkywi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthngoe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2abalejok.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2offqrrgv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdgzmqd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrtyfws.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxouyhs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsftoune.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlxmbio.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgwmhkq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcrggx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zufkyqvy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nywftdmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbvjgku.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdnvhn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgiaxpf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeutnpw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtucuqk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqhknig.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwifpfwt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsxatxg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvlsiwl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tomvtzly.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkroirfm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2edzmqjwt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzouunro.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2foyuwrxa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hryvetxu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vniuezqt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrrmmkx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zofujuse.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwibtjn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uocyxnke.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmrswjw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxookoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfjhsjp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbysheq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sddsdpty.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mptbgibh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrmmdkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhkuupb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwlvqat.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtsqleq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lghsmlus.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2scljvrzm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbgppco.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nelltwwf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ovusxxnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyxyfyk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtdgvnc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ladwiyop.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gkprrnlr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuojkjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpgttqq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmnqqqr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yggqxdzq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexihpg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdglxmr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhidrru.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsehvbf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcitcnf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivarbajq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqitukss.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2viudtvpo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyntldyd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnqiqsb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfboips.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atpvponq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvieiqb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwslnsy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioufdiey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhigpctt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qccwkqdn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvudgbgk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unqookcp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqufono.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zncejirz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdzadqh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjrblsi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxdzklt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfuapow.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tookopgj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwxmlvv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nuohqzas.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfsvglv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aypvbbpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yufwfiis.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeavxsh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pypltquq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbawgvf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jvihewrb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjftlnsi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dykfmamx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmvmqoq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqfakhr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxpspbu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tazthyaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bflrapmt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvacgbmq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2etsjsyev.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfwlnis.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkkipah.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrwnyse.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzkaceb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlfshqn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrojyyj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2deagywqt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiixvjb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2grrtuezo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmlsvzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkkculp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hfswkwet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utlpapnf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzyklyd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2amuqgzub.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phkukebp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpdnnyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxsuqjg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olxikrya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fldheuox.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwjbswu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrllmjei.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zoinzftm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnkxfwn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klshsrux.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsobvpv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojmlju.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bszfitbs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsyiqze.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2doelvrvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcuyost.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfbzhbe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhpwhjh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lviofttd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmifchcj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jisirkei.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzipvhq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2larnhxft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdguzea.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkutjbx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiyplih.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrxvolh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyobsrmu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loouctxl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdpkgwf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfjxojg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaazwse.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaxkeuu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjabdavr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upehvcqd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lupbtqpa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2apzoiozs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmnptc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhnotjo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rifmrjkx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnekumeu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqezukn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zplnbgyj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxqybid.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2burblnuo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpclhifq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnfbgts.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvdmcus.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkksxkt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcesweyv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwufvjt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqkjggf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jottutcz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2azstnfpd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqeibbk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkewgobx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ualxpnky.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tuukopik.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kydkaqqa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqoliue.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2typgupbe.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kyanwjgh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvehpjth.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyysiuic.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrfccgf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wamgkoyd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjtvpc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoewpab.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lelodaji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pofzogre.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2obvvoond.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqrylfr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmniemlh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmhaznd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkisiaif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwrzdxt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaaswfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhfdozo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiemfwm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvcerwc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfnlfhr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwzymzj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2orphehed.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2odwubfom.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdfyqpx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsflwpf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkmctcr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pffsxcka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xotrvztq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uieambap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znzodnxf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2syevacea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciskrlig.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anyfbyxb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisauydu.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iilqnpba.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2pstjjqav.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkumyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzqgocz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2angcyohs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lstlbqky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjadfwg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzedqrge.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhdomzg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrrchpo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqssflsz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwxbxdh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaeyjvq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofothhzy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nnznfnit.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utyfauuv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrhlflb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyskiuze.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cokvdczn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvzpngx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcereef.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwiwufc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevgctr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnpscfn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyfxvdq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyafcfj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2siipkweo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcsmtdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzfsyu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzglcvq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbhislf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgybnyub.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwqgawc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdwjax.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anohijdh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysorpjrg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjxgegr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2jypiymkj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2owwuqpwa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdjaawn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2punocnxw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2auzyklvd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghvzsn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zujsowoq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrhuiqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgnfdcy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ladxjzyf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2yyakdjdf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2rhylqgsv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbvtkgy.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2edaaosjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufcwmfb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkybffnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2sszesknw.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2siekihjb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuovmxz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvtisl.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zieajdal.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovnqhlw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzdwsgz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2erdzzsbg.html


<!-- 参考信息 -->