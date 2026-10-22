代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvrnpcg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xftstaks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krugquch.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrozsz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxueyif.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjraigwj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpavvbfa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emvhgpks.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiszfozn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiznhypp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2myakbssx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuscoqzc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuyolnq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tioqccfs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zorbdepy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afpmkbvp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvnwscp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnmekfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpnlxuu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xttukkdl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfccywjo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpprwsz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jejmcbxk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtdjdwx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeerkjb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qheoupmw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjbxdvi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfnydex.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhujqin.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2diplsmea.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aldpunni.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gccwtxky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytabdldd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjecysd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhgbpjy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjfmtr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2crujwjei.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqhjcaz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnzmeci.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vhivbgfz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hljxftmb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mapukzyv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmigwut.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkmrvmt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhtfrse.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2muvpnzoe.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hungsmqs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wikbppby.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2drwcsboj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpujyown.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkwnnfl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jonsqjgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijknycu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqehtjr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tilszeno.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyxtlvl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaddxuz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbavhow.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpajcgk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzvxhkc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxmdzpf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnudkhk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrxiftp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otlskkoe.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aolncsif.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwpanhj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxnhier.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oixrhsbb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdewoefb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzjwpvk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haspjunj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzvfaxx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpnnjfr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ushxzsgi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmujgrbz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2obsecjpe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwbrzeu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icezxbho.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvkoslk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cysaofwy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkflkc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsyabon.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajibqiqw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxnvzev.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbfkqxo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fujmwyfw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2blrtihle.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjpigr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jylypogx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvnkfig.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeiaomc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuvuofe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnqbemf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dihxyrme.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrgmsod.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvzwaki.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxvbqtd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqludib.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvkejvn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtvkhfy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwpzkmo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefpwmuo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alejkppf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlmkzyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybabiwwa.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwadbou.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiptmyz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrrhyli.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzudafu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfwwwai.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymvapug.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqcrsjg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwohicr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2higvkhbl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuietei.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wobonhxn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ganddyzw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlehlst.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2psveewix.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gulhmdrx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhverlu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnkagmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iasyiics.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2twmlhirq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xelhmxyo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpeecrb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmgyhay.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gckcdxhe.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnuqlqe.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzswlst.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dplnlzpj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frehehyw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nibyjmpt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2stxjijoe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkcirhl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwkrkxs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkalpvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2goslimij.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2awdtprpt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vfciqdji.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tybbigju.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vslcygab.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrouwiom.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuptsbrz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jomiqbnn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yatstxhf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kclcqeuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyerces.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxhxysg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hujfcrht.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kmswhagr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfusnsbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwebwuhc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjlllt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwutfjvg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtzkyow.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpprzrur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzmoncj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjrfpw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uumztell.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvltnlk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koagkijc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhogxix.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzufynzx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjttotrs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2feukhdps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfikxvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaibsyzi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzodzys.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdllbmrh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqacyhql.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avunhxlu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2brgarffg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdyqaje.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnflvld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcifvzl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2flvwbypk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etdfohrp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnlwjow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzygwizd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqpksgk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avlhipif.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwentfpy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2menjbsdy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olbanqzy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuxwofk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zaczjqgg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xxioaqvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pijuohvt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybivyx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrapiyiv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyxxnir.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenaorhd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrvfdse.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zngdgiyz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqxqrvr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2snxqegpu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmvzpgv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjyrmpm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdjvwlq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqeyqff.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2egujunom.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uieghbzh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2irbuzhlh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukzvea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppozmsln.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vltnized.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrvpcua.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yclcwosi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzjikvc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgunsey.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsqzzfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aixhpqle.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkgbdjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvelxcb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2olkloxuw.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaunivg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxcjjhz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkydkhi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkoqrnz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxpsvc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkytjal.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvhaiog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2lavnkinx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2quhycvnu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwvtlj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqeobbi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdksbtv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fouvlozn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflpgjig.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzpuhwh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqixgsl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkzxzti.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zttrfncp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzqapkx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjlcofk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rktpxbwz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbuotsj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2paqccydq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvhuxxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeasuzd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bulchthc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhongtea.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzazlbmi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhkisml.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsckwtr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhntkais.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmywieg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2znwlioxh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzmqgzo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcdhnif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2smsbyfsj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfftoyhd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvtbre.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkqkcnq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdqoih.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oebelhcd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhxchwk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuwqpbx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyhqjia.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qewwenzw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsimlqy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjvhghc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvvdpbz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnebjjf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oljeddsa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsuzhom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jauzmqfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2knsqvjgg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2nalowmpg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsvvkdw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfkzftb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnygiqn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2thwebfmq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bibkdcfk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubozdgjv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rymqisxy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmttfgq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqslhayk.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2onnfgvau.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyamoucy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrvqwkt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxodssg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkpjxbh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvrhxjf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iymkeldu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqzhdzd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2brtvlucy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvdmxs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2bldkiryn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2weclwuhh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2bceiwdhs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2avgkmfeq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgcrwno.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftnbho.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2lutenvqb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2allegsgz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzvnlfr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetbkseu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2juomicag.html


<!-- 参考信息 -->