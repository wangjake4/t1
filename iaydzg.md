代发 wailian999

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdulmak.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oikqqmfm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2npovmakq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2awtcotnh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrkheea.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnefuyiy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvctavt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skzzbjgx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvjavow.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhohxhe.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaygslb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzmzlnl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qoondglm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoichxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2puxprqvy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tporgsfj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gputqrjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwfcqjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huvuwmxi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idxjrtzo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuuwfdd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wptuefoy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgnehpj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zltbxwkn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwkdkux.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdiigfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoltfco.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2evdyabjv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxubozj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmuymyx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwmcxnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpadeuy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpzyzbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsduxydd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqvdvja.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwroniye.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvudqfqf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatgtblp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmcbtid.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2htowwmxq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakrjjj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqccrdvg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmtrjcd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udodybak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oquwvyur.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrizskt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxyiifx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfttxyln.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxwrxrj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpxkent.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oinusynk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqdhnab.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nifqwkyd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgzfyrd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejdkks.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbyjfes.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vgducoig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qksbowdr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bhixacjh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2guxqqgjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hllqadno.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rovlfmlb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcbouir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gurnluqi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxblqru.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mxizimib.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clemaink.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzuxfgo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqcwbqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlipcxja.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlebdsow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2drpdfdhe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wttvperv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzcqlhp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjcasou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbagtaw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2luqhjfvn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglcxwtg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnucesol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2huzpyrjy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qimakofc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2foddtwoo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2trmgxvgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqefrkko.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ambnpdmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oahcbzws.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2urmfbvdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsbieks.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbxumzd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2binzytdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgvodpu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervaoawz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bppnbubg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwvuoua.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbivffd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hmazkzbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoqonff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwqkhfq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxwvlzk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhgphqk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urifyefd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlmsujv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcfhghk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miovpqrt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzqqlmm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fehubczn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gptdrqyl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjwufgu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2abwlicno.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajysjxrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggjrzva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkgbops.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqhjvzf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prevqkuj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjpahpu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtqdkto.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdgduxz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpenwraw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2affdzxyb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cahitcbc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdsuzuk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vleyowqc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeulnsa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzqbzcz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwwcpnz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnomewxt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szrqjtwq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laqorfax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiamijd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbiyxxr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlgylfh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2icehrxbm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzghpsd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctxqdbl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdicql.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2soucyjof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2phbrbcxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2othfegky.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatwyys.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2phtvnrrs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfgcncl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttawsmio.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpiagrn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpinvfn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bamhsejz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmvjyff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spltynyc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2olzothom.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoawygu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxrlolm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkdegwx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuvleqq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpdzzvs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqamnz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbppsksa.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycddisjz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkijzju.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrqbnil.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2druvqatk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsnqlgy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uueyvlgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixazuvyx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2clwnphmf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbyfmet.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcdyqow.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrlqokk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzlefjv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlhdapr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2oetlounj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2aatgesbm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkevxvu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ugchodhd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtsiewa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjzjvox.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjastbni.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zydwthrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yapbtxhi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvgtogv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpabman.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzodsbgn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcgwsuv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glmjrcuj.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdolgmd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzxaiu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2fntptrov.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxmywke.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xposnqni.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdanepq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2piuvfekn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnjgdqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2occneulc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2azvctydl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2beduzsak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yueipeue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrkjpvk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygccjbki.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tftcgoll.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bevcdkfu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsqwqbg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqvhgkr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2beflfiss.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2drcazjkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuxelkh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ydppsofm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2viipimgr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsufymi.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkcusql.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsqzlgt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzsxddd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2szdergmw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uarwbvyb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwszxex.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2khiiqbmk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmsivfe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wimavrwa.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cvclbaef.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exvrzyzf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njymfwwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aphlmabh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsnlltw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vadislhb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxtdmlf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2glidjlvi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqumdcoa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vybrsggx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2irskqewp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2edplgwze.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuvrhsg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgsdfmy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzvvzoo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2pifeccku.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwkxjt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxxradn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2orzqqmmf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjmaxxw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgpmif.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhvfnwf.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2mupmuzbd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktpqhp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwdpqsb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsupmqi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxgkyii.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrhmhyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkxlfas.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoukfcu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvsezxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfctqdez.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2meogulkq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrduwpe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljotgbx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2keeqbvvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zicexsfh.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoczyfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwalvhnx.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyfltkh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2utkajyob.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmbyaf.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnwusdy.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfercgxu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpdjzgh.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljxcyh.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2avqqedzf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwofzgm.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2btymwtrh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmnzooa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxzyrve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2giywhaim.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvozhiql.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoffpkd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2dporzjpy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2spasvvit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyxbmvl.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmljusr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2assxvxlp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2diakazpf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfpjfji.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2eutjqrxv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrtisvp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcguxrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2hatxetqd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2isuhxyiv.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gabstamr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuadhbsb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgilwsao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvmwruv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjucej.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqbjwia.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2koptrwxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkjfgju.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrahrck.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpugwp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeydlmsk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbakxppy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvnhspd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjsggpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsckcfig.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucwqbze.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcdetht.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kihhvdex.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2xggmozog.html


<!-- 参考信息 -->