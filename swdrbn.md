代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsdljms.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sektcmen.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqdsnis.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swgvzave.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akgcukvb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwgzozw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emkgpbtk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwrlpx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2izljbrou.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2moyqaenz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjhscpj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfbupbc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekofvfli.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejtdctt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcdrsfk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bejxyhup.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsfneti.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sebmxrmz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiiomxe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eipzwmzc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhgdlig.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2chhkiqhb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iokqezzg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrrwwpk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzixeav.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlvqupm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlnfsko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hjajptdd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiblahrz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqowrhim.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puipzhru.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jklxkvvl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eihroguz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kslpwayc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oujjohjd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulorglir.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrchhza.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmurmam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2unymxjce.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewwpfb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djewmjkj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tegpmlui.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owcynjkx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrljwnf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzbjuqg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrmjlkf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeipkvi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfvckki.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2byprqfmb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2isofgezw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzwnzrv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vidnceoy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2aukldaln.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iriqcchx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jcscstyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tltjmvhk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woawszbj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcpcnug.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ankcsnzu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghstbgvu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqyztkr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unyevtle.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjkysih.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzkvvfo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dopgjwez.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oifevppd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boyxeqth.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtddsqr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzogrwt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwdxvxa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqjhvhb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2albnnyfd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptfxxyq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yejoxdxd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxsljxq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2athfxsou.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdgxmgb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2alopvpmb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxkzlsy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2crcmcahh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sdniyerv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqghsmt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jflyovve.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbytoatc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzatgaih.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utjwbodu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2quigkepy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lamltktt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbfovms.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rqndxgsg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxplxaza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udgsnwpi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2izeytzep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihibdnpz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmzmrd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmeopuz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevwama.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbfanfo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2menjpzet.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dapbuwam.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyrmtlt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodztfdn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtfiroi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrockdv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2spjoeoxn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrfqazc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2znjoohvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmejwdx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2stzqhdsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbcpote.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwcqcy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdptflca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuvgagf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggobqie.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bspuoazo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyasdoio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvdmhbd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjksfxm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpmpbgj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rapgsfad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxqser.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpolqrei.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxizxeur.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwcafvh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxydexj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2aopzuovs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhkedu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhwrgsp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2agdgerdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzjskcf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhyyxdb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvhexjs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2udcjjlnc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjoenwf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqkjdbn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxglguis.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vliijqbx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcixuoi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2josmyrqk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqsvbfe.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfujcaez.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skjgbsta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqqrbrb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxhtekh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zexyevzj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osojyyjm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsgauwt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2atjstqvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pibgfcmp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrfoffc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpzltqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuczsyt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrslthc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2khwvgqun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grjmduyt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcphrnk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbdfyoa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2oucgrmqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwqgwnf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2klrfslch.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqwgtkf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgzudll.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkslcsf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpdympp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnkqpcc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbcyleh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uquehngh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxqunza.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtacdcx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwcegyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkuvhj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfvhydt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2thmudjfm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2knjabqbt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqffccne.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeuuijp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2srhpfgxq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2unccehwa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2utcddrtr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsrnkuy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gejaqjlm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaevzzy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2diipxuda.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpiicnp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsgcryk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzbxgzc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuevcrir.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjjgaax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlibec.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdznrcku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjxsgq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlaqxj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2eabrzwub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdsyhhq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfpmnbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2shxibxob.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ietpyuvs.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2siahnjeu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgldtnjs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqjstot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pycpvrhz.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sxromwar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epxvsrle.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvagjxa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnhissj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgoxppf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhdwlqg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsquzrl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaiqotk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawwllft.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiaobim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyabtrf.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cmckldbq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuufnfl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffivktnw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2icgmiwhc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2agtuffrg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iafrqddg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkayldi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsdnrel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzldfwp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeztdhp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuowfym.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfzfxci.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffynehqh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwcwknb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfataepz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2fzekrsuo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytijimag.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiupqll.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qknvxqjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgvryds.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjmlfuz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqidizcb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhyunru.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuszniu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzchjgiu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zptulxzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkvzdgp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2shwmjcso.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhmogwt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zumybgrl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqharem.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mztrnzxe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wibqaykq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kteywutd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2naoyzcvp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2apenxxlr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2whivzokz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyjrgrs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2eyimmbqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjqxfhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnlrrs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pymvtryn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxyimau.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2onjdnppa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2swzmbuol.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2etvadxkr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvyzdvf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2brsbyhau.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2wocdjqxz.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxnotgo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhhpzxh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvcrsks.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqarjuz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojiigfj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlljkdfn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2ksimimuj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqxeycv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2scsjuxgr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2irafuiah.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfxnbyx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdrvuhd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfgdpam.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvovzgyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzfqpxv.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgtxsgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rspbsqor.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlgamed.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufibjuga.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkllaxy.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2klcesyez.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2smvszmog.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpcymsm.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqggsjd.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2whxlkzod.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2aasvqmdf.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bbucfioh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofulocdh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkbwhag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqngmgx.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwngxre.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdtovse.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhhbosx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2tktzmxlc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2lphuvkkx.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2qdboxwwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvnfxkm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2gznfysod.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkrzbyx.html


<!-- 参考信息 -->