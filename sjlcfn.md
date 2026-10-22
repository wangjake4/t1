代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auajdqpz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wyelivft.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2izrnlobj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2erkdnsfw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aevrabqs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkdgsco.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yicemrhw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxekxkg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2emuvejhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcwhnzk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbjyfny.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sucxlkyf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwhvxrz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtbkxvo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmfcxsn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpcltfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsukgvz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrggmpa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaigduwd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmybrmu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvtgsen.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnghcyi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwbrptp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkajjxys.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjzzhof.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2otqypjip.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkyvnmt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjtyykk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pwefmgvp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsiqjjn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esotomoe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjzvhbq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiebddr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaijkcps.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rouqfdka.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlzluyw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2reoquhbi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmbioiz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2icmdkqyi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2trelflrc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2brltcslx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqwffpr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcttmdwm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2crghsdpa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdmbnjr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2brkfmmnz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vizrfkwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sswidltg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjarlol.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xypohhao.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwilshtt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fydmawvg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqwjkpb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjmcdyf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhorotom.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpsqqin.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bbegekkl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhhmnlw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfghthy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcovajt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poqwjyql.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrpakyy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crmsjadx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlkesl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqtdexc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vibvnyyl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmubfij.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2emutuarh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aommogsk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2brozjwwt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrebzrp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgfdwyl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnfripb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2apxwkftj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqqsgke.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcidxbvu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiotqjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqnnddp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnqxuls.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwjmwm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sytdmewg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqyrwfb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qquhjhlu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpibxuw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcypqjc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rantrefw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxejmdy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwyrkfr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgyhlch.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymguthml.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeadztgt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acveqtdc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynkqsx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exnplqwt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2txktnzvd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yovsmmgj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdanbny.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsysfty.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqpkxwf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bwucuyxk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bodmnmun.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zujpczry.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzbhzg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2poooumxw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2roqyggxm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyhakxw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyzoyci.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsazmfn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bofypjxh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmtpvfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eacdcull.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qasbcset.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2orvkwozt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cobgrtmc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2owagmabf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqpzhyo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2npzfjeji.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphdkivu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmahyjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2czikibck.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbreczdl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfwbiqe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcjpgdm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbrdjcr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkpidg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyiilew.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzetcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiqisdb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxuwnfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpxdbo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfuptmx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvmlmwj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmalaef.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwdflfo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjwchmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnqybn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkgnayd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaxzidt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnmsais.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2czgrmuqx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2oogotkds.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmybrkjh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtelgdv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqtvahs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jicvezvj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nudfgwbf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwleiuq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoquugd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoqwixc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmrzhed.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2safohlmj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmruwrpe.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqmhlof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqzpkqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzsvmxp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyabkgng.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwowfc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxgunad.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqlzqie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbmehwp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xodyxqvg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbziaxdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcomseh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmcawgx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnondivm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvbzyti.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcklyaw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kppowsbd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuuafpc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uztmnjlg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fizlvvfc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzksidv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziilryln.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwkhznm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjgtyvw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbkygad.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vyubvdga.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxnjdkq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ohealabb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhmuijf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganmeeos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqxtxyy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2seceuipg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqovfov.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qfewcovs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxsrejm.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2onfjejsi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2urcfsqjy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwpzkjo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuvtdqk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jiefylhf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2myvjzqss.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmrsvbl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xrafahso.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbezpio.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nomvijls.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzotlia.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxanocq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlirjss.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2arfvwzbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dldudnjr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2avlquxnf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnckirs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmeuyp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoiykfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lliwlgvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2evddesjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupcuoqr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kacxiwdm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyufdjc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqlmoti.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyxoiuv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2radeyyaw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zycaetuu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ooggrjct.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hjibybfc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dglkxwty.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2puzfukts.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqzousp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltplbgkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskesxn.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkzzci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqmqmzq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iihjhign.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djvzuhqx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bieahvjf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjouags.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jufudsvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsvziak.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjcvgie.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhhqshi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2djrnjupa.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqipgvt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuyayvb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2khwsalgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2recyldvh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkebrvyf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuphjcmh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihtvvhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpytfuqp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmbclry.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kngrvixo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdekhlgc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iximscjo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrisuvsa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxjlzmb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqckuuc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuviavq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcenkdvv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2msjgdtyt.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbkrxaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbntxklm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpfzfoq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cktpmqzt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2turdjqhg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwtrdmp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwaluod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fywgnkyj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2plfewvcx.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfkpjbi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwxhdtq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgokpe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktzgppf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxnapac.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyngsqg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcfmwj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tleelbub.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kerdcefm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyllrwws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwhottq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2etidiogr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2vbodmwyv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvudpfx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvjmuj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxkntr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyaggmg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2keopclgi.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaibees.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpswheuw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2opdpqzmo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2oorkxuea.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2osfsjjob.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2rleespbe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrmxgc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiafceum.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjditch.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqezosqv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2woyyyukl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2sooryrkz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxijwzd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ialtmgrb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpbztsz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2qsntjhxt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnslgsc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2eacibgnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfutlyjl.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nyntkrgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuzdvwd.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbahoxx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxztkxkx.html


<!-- 参考信息 -->