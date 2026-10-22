代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipparyto.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zewtnwab.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmloxdtm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xszpfmge.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkoipno.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxkdloc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxkoop.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eecydmov.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrmkpgk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwioadiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbndwubn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxgfndt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2etyrrlde.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dykpqewc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2twpojsre.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dczbfrjm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mjetyrsa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ihavevzk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyzcdmk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyyjotm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2diqanmrh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcopmwn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zxftioal.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzlbemm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eraixmws.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdxraz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njuqhciv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzoziyq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nytlavuo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzcpryy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgeeotd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2olrfksmo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwstoto.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwibprq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvditxzj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhoenme.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkgqmti.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrmcyax.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oigdvhaz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uamkygam.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdjkyyq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuagcan.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxcahzp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkigajv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hahzjpxc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxocmli.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycehrfed.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kexyshfc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bnibpftk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2migciszi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbloftp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmhpvaf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwzatza.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eebgohzh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrndxvix.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdhdnyg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtenoon.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mrltxybh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfbhopd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flocfmcz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tnplzkyn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lirdawhd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2isttonha.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2htjnyblv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvbndpa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyeufjp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiocqez.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlvzjsf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwegckly.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nixndcua.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqsootf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuczwoi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfnfoph.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvrzspt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2quriazfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owccmqex.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ingrugti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmnimny.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2olaouuaw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgjncnu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqrkutl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pholpcaq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqmvzog.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iloogjpi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aleswzvi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmgxtcm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubarcvyt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uizdcxlz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekgudj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqleft.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hijxaxht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnqjtwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2admgifxu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgpfluu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdhcbhc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qimesaux.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjminfm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kivnureb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpsgbz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fenihijx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnyzggt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2arwximqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpnjnjw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjnhfv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcwopjj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrckogr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2huasldgy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxhqdeb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gargllnq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoxyiwx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psmxnfle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucetmbzm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypppcqyf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swfdpxbf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eshfhtgl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2amttpgbp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwkavqh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaopjlh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjldsop.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fstofqsn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglqnuhq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2amwdneob.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyjsfnv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wimlqbfo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrnylka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2daerlfqa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kguudqpw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsjvztu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwmzqeq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwbfzom.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evsrbrkj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpvckzx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ztomurcu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2inbueodv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcgeyqb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2turiyxhs.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklblfff.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcapxmw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxfgovg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tihtkano.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2urpdzuni.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnxuzgt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpddungj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjgddth.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjumsjp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopjwlyq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngssbnwc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uowskkfl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtfzob.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrypzam.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2foqztwmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzcslcx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2usplekms.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeybrvq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiklpjmq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnywkkto.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrhtsps.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2caimfrxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2haphmswd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lyteajmv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghklxrcv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjbqgd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tobkxgza.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pirmkdfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2sutwarmc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbtails.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxpyqrk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgouicue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqacyvbe.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtzqmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqxsepc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqnzav.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpceowuf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cawsmghg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxqktuz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyvgtcj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgoxaqy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qphmneag.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuaifwm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jazihzmb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfirksf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cipuurzw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwlyfco.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlinwdps.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjarnmru.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknctxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssmegvd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufdipaw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swaplwxo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqtpsqf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqqcunp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsctnwes.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfabhaa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cubpzoen.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgcyrln.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnldqbi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhuttuf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrsitta.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zupoaxok.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvakyzuu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clafivxw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lntoizcp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2drutbbfu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2epufcxfh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2duevyjch.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxbafdc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqcfgik.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cugxurrr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oounpwbp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjxlxlu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuymrbmq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzflwntu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhpuoy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffhdkc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2krppzrow.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hotqhthd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqfsbto.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2apzsedwu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgdxlmz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzghdcn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dopdxofp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfrobyv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2staufdkx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2klkojcjq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcypofqp.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpldlhd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2sallmfxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2erykzoot.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrlbwkt.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2grpnroks.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsruzfqa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvmsqnu.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2smpvquph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnthvxe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lminrdor.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfutmzk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2rssuxjcl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tttzketp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyvehln.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwzcqpb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2jyerzbpi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eibwcvdv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmpzlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mperghku.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2swfsyatp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnbyevy.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgzyndi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2zemcjefd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqmncly.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mycaqmhe.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwthlbgg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyblzofb.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsbhtes.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2qsblvgfi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2enjvdncr.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wysjwhtx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpombggb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2herxppfi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtelnzr.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzsfvey.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2nuafnzci.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2klwplpgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkztadr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxwzoak.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2qyekpfuj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwzettp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkselrrj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uitkperz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqrrpgs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyhezqr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoxjiqm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbturgx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzlolb.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbikcen.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdypnwq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssraoiqr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlacutg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsuuuwf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2huyifeaq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhitpcue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsitulg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhempx.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbyaoyc.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfzcqfw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnrwzzr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfczcsao.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpabkclj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbscfwwn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulqvpxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoynuar.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqbspil.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgupjfx.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2imbymtjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2heisscrt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2ergdfnev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2duvydqcj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2irlgbewb.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2uswcnixn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxslphg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfsdjlm.html


<!-- 参考信息 -->