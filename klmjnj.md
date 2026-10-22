代发 wailian999

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntixlwes.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtwrlbs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnrtvjt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqrizvy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnydrly.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiabaqf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhukcdwz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aefbdtgl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfmfoby.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yskhochr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnwfjvj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkydcrm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmmqmba.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgngiapk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbfewpp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdbjrah.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyydqzd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aiocqbcj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2geueajxg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqabrik.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwohmoi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ennaglfg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwovjjjo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmeyvsg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeykujyp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtindgs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slnppnup.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxvftqu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2chjuehdi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrorwld.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhetzlhd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuppxoc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkpkfdv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2urdnykmg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aifkiynh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepkdyp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cpurlnbn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yttyfrmh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lifmkhwo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdmwunc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsfhzop.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smefphey.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvnolcw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavcvfr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqapkisy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbcvhiv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrswmuhc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtoslmc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcglxrek.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pznvrhhu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2voevicmz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2frywnsem.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xovvxjch.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmozyqm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qijcqyrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqodkww.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lidezcpd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blzcryjd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyocwba.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiipukf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2asyluxrn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2remjyrpu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhmuvlt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2igscnesm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rozjubtx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrabamiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbcokxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2husmzfvj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwovyqsj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlnvetg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jijflmro.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgylxdm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tlngpkhe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdaryse.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iujguifn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2szglssof.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pydxjkuj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkfesen.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyombgs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwtabic.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yutnblqc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzziftl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2flltivps.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqimilst.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvvmrpt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqzfkz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoacjnz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nedcameb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tohddycb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psmouinh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxftknx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaezoio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stzbwjba.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeeiokj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocllzvql.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skkinsav.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtcicis.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gorynpaw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aptkyjhz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmqbrhn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2muntdnqh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtoqnas.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yclausfo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbhunvz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgokqt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gviathls.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjndhonp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cismggbo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wschnydi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2percdsau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2peamklbe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlypakpu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqimgmgg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyqhzrk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfavakt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhrumyu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwyktaz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2saxjhecu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpdteee.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnautaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiebtzx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zraszzkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvwyani.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wffdlwbj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpcyhcz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxaezyz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lcysvoni.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mznbjxah.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwngcwq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchxzabb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppotbdv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlbmxn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqjfapf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsqqmot.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2slokcnis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzbvuab.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ocufmivq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2holmjwzj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhowacd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgizwda.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuizvwhz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhsbvip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcorhmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvhudlk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzvsofg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysywdhue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfetymp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2krirbufb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthzqfk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppcjsxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwekrduu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmathiu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlyvbgy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbnceyg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrmnrdt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzlbnae.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphwjec.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2okglkjrr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbttvxv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2birzdlkx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtkfoi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrjqkmi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbahqgzy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fatbnlcm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbonvcq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuedtch.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gatcyiqz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joncjmrz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wordjvpp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwvfha.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnxrxxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmysuvff.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvxmlfd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoduzxf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsmcusl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwaozat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znmbxerj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzelyfj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwssheby.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njajedwz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmgaijk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqwlsop.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sawmplys.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxxsdfw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2apkidxys.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjawwtq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gxefbxxo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsqppyo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqccgqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2beczmzcy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2doqfwyii.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsbyllu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjcblnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zweybahp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfamqdoc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhqkuag.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnrlrxj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqngvzfn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwxcdrw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bckywggt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlffiah.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuzqcys.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbppitng.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvcuphp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2wphnqaok.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpynyogg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yamqmlxc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmhycyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzjzwrn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oelbhljj.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvycria.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2oobiyvhh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrrpxsw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjeulpg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlppgxev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbocfqz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwqfsew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkpmaut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2spkxbuvm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lorhkrdr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyxlqsn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnsxobm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2owmtdjaa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zluvdcjv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkximnw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfxcijv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqwxmle.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2azuhirez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhjgjly.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tguphatd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvjsbhz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tiplkaad.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oektwabp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnnzpcp.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgfgorr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2islndvqb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqlhfuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipytzjec.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawlcqku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhyckhj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgngpkby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhbybfc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2knxqiivf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2scltmzda.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzeddsf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphamlx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxzcebi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgemczfw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmtlpnl.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yckhrjng.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytpcmhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2woiopvoo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfwqelu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtxnrxq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxxojup.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2pephzdrn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2orpmyxzb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxuunse.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2myngpmsy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpsnncf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxicvzvd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2twkidvbx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iungpuqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkhjoxm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujjxim.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iirvfyhy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmpjvtu.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tbymtvgj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2foadgvgp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhlizli.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpllzsbj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwntpps.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaxiobh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shtyuess.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjkpmwt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2miykobwe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkxzntf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2chrlueig.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcimqcd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mimggrkw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdwgjgx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2awxnkmvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqbwmai.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2qziuinyo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iojhdvfd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwumlim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2xntgafri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2idbdqzhs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwplfvdf.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2dxshtbwj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2ertzjgzs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejigmzmj.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjxshth.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdkxwzm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axxmqlyx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqsqvcz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlianko.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sliyqilv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpcmway.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2dntuwwhg.html


<!-- 参考信息 -->