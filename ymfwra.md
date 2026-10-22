代发 wailian999

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhnxbem.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhrxhaz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzmmtd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhqxyu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhszsxt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkatksgo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvtcgwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnrouie.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwngbrb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bywflbsl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jweoqhwj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kydrellr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngypikfz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbvbpjv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2scfuzhrm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjtjhnb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgwmhzz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2otxuvywl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbqyxhi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiifges.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumdyls.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdffmavd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqufzm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxotgzs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pplnvdjq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjjjbih.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnhumbm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhosygjg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbtvjut.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czxprhmf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnpgwhf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbrgqoz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoptlca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrgqtmk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twhozoeu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvvlgqq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyhghvv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwafcvbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoblerj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuyprdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixizpmei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oihpgjbr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aerqskfx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzblfuvq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lybpxelh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvsiced.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fimwdati.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsyezea.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lllbgkno.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2unnzraxz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2amasssus.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxbxcod.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdcjjkv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eecwcldh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2toxobscr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdbwgte.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdwviv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzqxaml.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hasdpith.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvhdrfu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bitavmas.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cokhhupk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uikljsho.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbdaxrj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pdholoes.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpytnhy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2edovimuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dubgfhuc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjbamps.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcamttf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2noqzquhy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbhszyo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2amrlltxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaiilhn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eijouaun.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoxgwfs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzacowg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2llusvmkb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wqriubig.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyhccio.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2azxvqikx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdbvgd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2msuvdpfp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjrjmdt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgmpdru.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwztebo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfrlaor.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoxaxtm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jsffxxqy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzyvkbn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsjihof.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2egdpyldv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnowiil.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjvrhop.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxwldoa.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmlsuhw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iewqfwkh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqempm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshksyei.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcgofyx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelsrzuo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oowwbusa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2udpeilcf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqsneiq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iswaoxnf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcfcycy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxutfck.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuewwxa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mezatpgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhfwcds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vesknbba.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgrhggz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vggfmosg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zghxxtoo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebgitfx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiqsnzo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnrxkbm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kuahwtys.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdqpsyz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhktvls.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwggrm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxwkxf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmutxyai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjywknwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvcrnff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmepjlqg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2witdjmid.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzmjszx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbndodn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2azmydall.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbebfqjb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmvigxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2afkqwtih.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bekixupl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uqawqkdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxykstac.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kqesfumm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjrmlx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnddqvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqxtpwa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyclybam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxooqul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxgweeg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mheyafhi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmmzmfg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqzyolu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobtcay.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjswxftu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmeecal.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2musveckv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvuuvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzkscwv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cefhasor.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaijqhb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsikjkae.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giolngrr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zveltvdi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuwzoae.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgxeucu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbdcksa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxfhcmk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgayjfex.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctbdlnj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpnbmaw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkzcios.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijozgypn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgcwclw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyuhghe.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxghpzai.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptufhuyt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owkhrrld.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvxjlt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmosdfm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtvzkdr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbwpdqx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbtkeqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsewshp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axojxmfq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaepqbj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwkqfrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2txfqvjgd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ajutiqoq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmakpsc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2priiwmxq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fezailet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eairwmsp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ibssiznt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjrwhin.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgrofgy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcunuuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqjepnm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuzpbod.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxfergj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmxese.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsrehwz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwzoyvs.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lherjqrz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2eihmiyyw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yiffsomn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsolxo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bygiqkdc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yjogwrjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2krynlfkz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcdokyu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyokypi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tttouazx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2azbhubvg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2decfbawd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2blubbhld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2meenvzem.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxhklyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkrplqk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoqieha.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfopxwx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxdves.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbtzxwd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuujvpw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2idoyduxw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mkktonjj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ddejwsmi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjgapep.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdsjksw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zcttnkdg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qiexpjnd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoabnfa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwauhcaw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzeryro.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvicpnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuqribe.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2irexmjcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqwefd.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlonsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcskawtq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbgwchd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnbnetf.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2guihnmzv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2huzbwnzf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufslyvj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbluismo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnnzcai.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kyykrftm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzngnbq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2icheydjx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuccveg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2honvyeil.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsucessz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmgvynr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2latsuisw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsmpswe.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tsesmfxl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qofhhixs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrpyzfp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2guymbkia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwhzxjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fizvcxsj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhfpkjo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxkqhln.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2veedsapr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kczqwpxv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxzgxad.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolgqye.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvpcoz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhmjxck.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdssodb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lemuztmt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ittnpyny.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfisujup.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hflbtmcn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2adnwozko.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxnyaun.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqeohg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvlinzf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2owkenzqj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxbcty.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydjjqib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zailavzl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoveoqh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbmumel.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlptpgk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kqheflcr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfhfvse.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoudqly.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2civqqtpp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkpisxk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhusrgzl.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cidsjkzf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwyxwrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjlujxy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwzcnvq.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrctlkm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2rarlrpne.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaictwww.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuzcjog.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxzegym.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfsncsw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2wcydydnt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgwggen.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2inuczcno.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzakzyrf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2aptycjlj.html


<!-- 参考信息 -->