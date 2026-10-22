代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eumrepqn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bkknewvz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2emhawfxw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zoostdpr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeeceyt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2octiqata.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mypdghae.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2owfzsfqi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2okgrmwpk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmjrldh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wseyanbd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkzesjl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umaexlht.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2useonilv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyaxsct.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlwgrsu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtterkr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxarallr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkwjypb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wcptxbnt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nopyevll.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrnuflf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qzorgwhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhmwieq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoitmyqe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuhzbiv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcnqmpb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wewpdcjx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uptixbsp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwwqotj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwouylb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoobiww.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tetyaxic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvuwmai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwmheac.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjipzhh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rwacqhfj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwjaogf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvykfz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznunzfg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpctnfnk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgmuxkh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbyqkfy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fucaotsb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzbsdlv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbjcduz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsqsmto.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyamrgj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpezbygf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocbauj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekheyqy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqulqgab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzutqgjx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfwbdjf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnonbwpz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcehnzuj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2duygcwsp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tqllvcjf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nsajvgby.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkfmoxj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kqknsykw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dscbopku.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgneavp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nljwpkhs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bopwzsse.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ctunvlch.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjevmsu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mowretfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gozofckv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfzsxlg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeutrwxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgdwlux.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjerbpn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2youutasw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kerzyxko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyupqwtv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2feaqrycn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqczpywq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2egcjzfyn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidafszm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkjhsp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuzizwp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trzcbmes.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpavccj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgonfaog.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubxddtt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gougrjcj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaxhizr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlmtrau.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oftbakrv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ysflvwjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvicfnaa.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzwzhkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iplrcwkr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2twbasrnw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qculgnpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uugfzjen.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvozjib.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlutkvw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrmpsly.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwjtjqu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzfsqdm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfqxlfm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2itusafnk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxazebbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oraiduxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2korsuujk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxdbial.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkjukuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjfumwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otgdhfsk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldftquh.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqihwacp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmipkeqn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqkwhbd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifesmsnw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mobiyukk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqekekl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufybtksm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mockksto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqsgprl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agacbtnm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pziwztml.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alzawyvb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftymbvex.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jijlerkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjhzaz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdyfunc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolteun.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flrorztu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2boibalpw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2keogkpou.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftjdaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjulclzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsulixm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzykbnrd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtadaxfz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rkifpoeg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adbchmqr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vzybmbxf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kyizfomj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2klyygmls.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnskupd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvzjmrq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbxtbom.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpydrpaz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gertruwy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iqafwzjb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lucpvbmv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2smxjjoii.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvohxoew.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wloearsr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yolrisrq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjftfdu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2caaersns.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrwofjr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jivenanv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2etmabgwu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmbbdbx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuifnkt.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lntfoxvg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagwrtsr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrupoca.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceroitda.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bzackifr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2korwmikz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ymltabct.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2poxwcboz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2whonpvix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayslezsi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqgnrga.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xounvpgy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2limcndzw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2eurrmmex.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hobaptoi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2czizvkoz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoliqwh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkcarmm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdrsyqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2imzqxxfv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqwotxu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbwpasl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulejgpns.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2umzllpyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tafxnqyz.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qziezwzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksenzeig.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2frkdltjb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywtbnnf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayigvqgr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2udsjgdsv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2meldlbtk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hippdcpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgtaieb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwmvag.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcbbyfw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfiolc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnylymbd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkudtkj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rscgtrre.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwegswbu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gppptgrw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xohoyauk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvojidv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqoecqo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ducilvwk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqduxmc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwvfwya.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtrfvdd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqznazzq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlgnbsr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmhzuau.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wudxthqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jryuawia.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrlgenf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyzxzig.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eligxnlg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgwjmth.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2srkbrcqe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtlovw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfsdyzh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zszdlvlu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfeejw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wwicmlii.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgqbfn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyogfkb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeraswtx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vawqhvjn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjclzfh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzumfrbs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajiqljm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vabiinqb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2erzqfpum.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuotban.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrvsbjj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmvmwjp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2crjenhlu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmcflmk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdpnapd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhvxysl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpizrrpi.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnfmlwx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2euecuhmq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupqcipp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkesgce.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2dphjyfcz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlplllcx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckoupxo.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbmrac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2picbcuxh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnnxtiz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2afkbekeu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2yowhjxrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohoaszl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvznnpb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqshqjrk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2zoitduqd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezzmwjy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2olikwxuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgdmzds.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aoabqwcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnloylha.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdapviq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxdnlth.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2qspurymh.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtxnnou.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrxigmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqugqwd.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gutckhkc.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2yyetbyng.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeagkre.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtgsgei.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewkuhve.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhksghx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrmgmso.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxhyyfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2qyanntql.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhkrjxf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzpvqgj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgnciqo.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcrzesq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuigojon.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqjuezo.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2tolddkyl.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2udhyvhdy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkusvn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqyrvj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnhsfiz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdhrjvd.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qcajuaer.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycijiipi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuudajja.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjzjdcz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2nksrpard.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbdtbru.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvalkgm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmousrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2lepixrvt.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2erdncowx.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeeyslp.html


<!-- 参考信息 -->