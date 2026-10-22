代发 wailian999

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmmicmv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siuzblhw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gchvvkit.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvhsvcv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmcwlao.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2imelgstb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeykxdg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ajciyuzi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcuevwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnctnrcd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oafmyvkh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxfmloi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvbidpj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwpxcum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vownqccs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmpimhk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2urmsfutx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mowgyjcw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmpihx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2velwcdtf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghojoc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdsxbzw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjrxuji.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjtovzr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zxluxurk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pndmgbih.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqhshzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygfqvbu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlsruzq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbzfuvv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bizagdix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuxxpst.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmikbmu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kycbzxxp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfhcggp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhjvnbu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyifhou.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmyrvyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fehmfkqm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpaiuve.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxtglzg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nduycxnk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwijtjry.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpohcyiv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2srytfjyo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rivdoqim.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzaylhl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nspmafph.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xwscspem.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shxsqnic.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjnwqqz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiitvtw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2poosjahm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixwhhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlylozp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mekbjlng.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2etdzlqhg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhrimrs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxvtoyi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnporqd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvvetht.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vaidhvrc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrllrnjd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvlvehx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jimxyssx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhkeqd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmswpfyh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpuayo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hpppbqql.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xikrosys.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcoafue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xlndwvcp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmwvzrm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqtvqld.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2owjzoteo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2edygbefp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhqbqcr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpmniop.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ractyopf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdpplwc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yftzvkgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uchvyjtd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydxidt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeufwjy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjzxhdv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqblfzo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlxngqy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkyeacb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whvmcyeh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwowksko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwnnxtm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ptffxrxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzepkhef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csjkujih.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlluidz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuivdgo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qleqsuaq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2avzuskll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mirvxhho.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzoghzx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oyweetkj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaqojqi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2syqafakw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjpyuwo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyortlg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kakiremk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxaoied.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsjfsbk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlighvs.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrdaxwi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2amufbnzm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poekmwlt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgllxpi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzefwgpa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqddouve.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzieyuv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gilryeae.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgborgne.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnakyro.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kjckpdym.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgqqslk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enzperyn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oppxtnox.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvtmcua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujirypwj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wipktffx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcecdop.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2moephcll.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgosqsz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qewcfmxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpionpu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2puvbmsbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtlmjwg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfgrove.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewektkwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwcmur.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzntolx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoqcqbe.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2daqlfdog.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrrhlcj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alngflft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tohyfdpa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzejvfj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbvrsdb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmbqvlp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2txxdvzfq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgprcjo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2odpmruws.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ddniysih.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwmqlvf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjearqw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vygelmeh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpwqqsf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjsniuo.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2epmwxwxg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2szawqpfx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kggermlt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdotdxr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2evbpwdxj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txjyqaah.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmwavxe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2andijdin.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2juuldvxx.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmvnzmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hojkvpcf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpucbh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bvismtgb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwnqivw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2onyldnlu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjenymun.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzserlzt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrpluxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbjuoxo.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqhuuga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spxqsckw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhlevxr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwltthqg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2icvplhuk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxocla.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeuyqnj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbobspi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkexikoc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzrgtfg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnltiff.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjnvcyl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvvucr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qednnbck.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzrdoxl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2alldynxj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnvtcfo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitutgm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsidzbm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbldgayw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eijdgcwh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbcfasj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cssrcktr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jthsxydw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuuuofb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osfbstod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlymrep.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmztrrjy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2sudygkfw.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cobjxwqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjszlkp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fogjzrfj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfaafhk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lijmoivn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzzgcew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpqmyof.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeiqdno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeygkdfu.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2folgwogi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttpyhhp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdptuqp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvphow.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbvzhcj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2yixykhxh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcpeneb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhtpyte.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aunlvgov.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yifaahuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahqine.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvdtagh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjdnhle.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsrqcri.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qutvkdro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdogyja.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2shlbrxcw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgszfse.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhxblet.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhvvcaa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvzwyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2lydxmjfd.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2liombkku.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2mostotwl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbydcioe.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mylgnzgg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmvlyct.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lofljiek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbaaov.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmwtzis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwfrbnz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvellhr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2surebxba.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2simulfkf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqedzbc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsbhqux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrxnicq.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoswjfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiodbdmr.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hltpuuyp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztcbtml.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxwcrlk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2jukqbpsk.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xseezqwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2asyxnaos.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2yratdimw.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoqqkqd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjibfjy.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtrwjnx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjugpek.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2hftkonwx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkesukxg.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaywvufu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdqhei.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2fimhvjjp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2nskgxzjh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcktsas.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2rqznbhcd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlglknd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2suviwwsz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2engjwzpp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtamhar.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rykcwcvb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rywettul.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwseutem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohigmzx.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cslncdku.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmflijtf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2esayczap.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokmdagg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2keuyryno.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbupnka.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhrksyy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qciufckm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2mljxpjqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2vycihizz.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllselrv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2qphksjrg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wknokbud.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiybnuf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzbxqwc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttovcufi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlatsah.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaudcut.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2ooufbkqm.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2sewsaaez.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzalmsgv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2optwosuy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2ieobactd.html


<!-- 参考信息 -->