代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dygzkvsi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwicckuc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2afrspwvq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpijutx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mszxqxvq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxfqywf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuliutr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lymlvbme.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrskpzm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2klatmtfu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtgldgv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kgowmwrz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clmucayp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyckdfw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtcdbea.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2audycphw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsniurl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqujejvn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaxaxsu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmuewmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvbpyim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilckhou.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xkltojpk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawwmqid.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkajwdi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fagqelmf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqkswxv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akzncisg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2msczjytg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxqxhnz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2npwmbgdt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2datvkkeu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2coqmwmxa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2waplyxzx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnrdpxy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pybaohip.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiuaqsf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uozbwksh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjsqpfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubrzgvr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqabhbby.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2verhumda.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egixulqj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoijhse.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xncaqiop.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpentoo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmwkfh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oermfwod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frlqmqrg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcnbend.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmblgyq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdtumua.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdhuzgz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaklyimv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzugbhjo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akbwnuxo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbqwzae.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bgthqpgy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwizibmw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oclqoezw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdtzqqe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhcfbwk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2onuqxsai.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpivwsn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbiqwge.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcpyyxv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2szxumqhk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbomabo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhbxtom.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxojmzis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwkerqi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpqomsv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdonnlke.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjadzsfa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeedivv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfrpnkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ssldcbxu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgozeorb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbaldwn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuuzeat.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2olplnxul.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2leccrahf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdhrlrg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoxbdvc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsxzrpk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphywylo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zevvpzru.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkfdggx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2azrrvxed.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuchlig.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvhopgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmnpnxx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdipnje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzaixpb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2keudtzpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtaguh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsgcqto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goitlhqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trxqdqfn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kralmnxt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zdekhdaw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddofsjok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zslenjzl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbsbayg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdklqrug.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdemov.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmiercl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwlddtk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knhuvvwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhbwbna.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nccelzcr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mshlhuio.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edfxfbmm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycjmgtw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bovvdoga.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqupmnzj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxmtrwc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqvyvvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwbsueb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoucqzcx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhjqixw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsikcpim.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fnigezgt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pegtbyjz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vorahdhw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfaejz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tduwemmd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuuvvtm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoagucu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfisgymk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kiparhfj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxydapd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcceyaub.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfmiqmc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhbjkhf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvatjpwu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzizxq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jxanfsrr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czscoual.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2amqprkkv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rgowjcym.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfsnkrb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsjtoqj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzeycs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zagscldt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsumafac.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukieigpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbvyrxs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuiaaez.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrjxmwo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkfivnv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbufryy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnoypmb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rywwjbru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihhggc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsmdjjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lykxjhxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2syllmyuz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ettimkoo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjclfosb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cboyfcxz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzxnqog.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2wffgunsd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeodmycn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnxzbbs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mdowvvkr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzdrdgw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ahthxkua.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2czsuhwam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ognskicy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaniyst.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pokirysc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaeqgff.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbwkgds.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqseebl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxsfypr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjnkfjd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwhfzoj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fudqjdxu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mmanmdpu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2edgjsezt.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2flvkbutb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkyomqj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaqlcku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrwatj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhviqwqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqshbzcy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxsvisc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiqikca.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvncuavg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srmxtgra.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwfioxn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvkfcdc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glfxjsza.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvyjjip.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqueffzy.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbazwrzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinliwni.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfncoyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhxadlu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbwgfmz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpikstz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywayoxk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqcasky.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lroqwznw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxapoie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efbvjanv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2diboeqec.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjdwfvs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfjqstg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mayufcxd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xevrotof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kweqswii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwfnlou.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igxmwavi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpzxyaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axdsbwgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2soxmsttn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqwhgls.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2orkggcyu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xazrocqz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2knlgzsor.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzgrnwr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fuemfpdu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvicycb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeclcwl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfobwre.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcrpwt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxfsauz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hstlmikp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbqpbhk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2umiwzcpl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhuqiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2sugephpx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2mihmegjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ycleqnoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjvlcul.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2aapdvptz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdlnzzj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2qgotiptx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkxmvmj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgakhox.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpivreu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwidmalh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdsuenu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2igvyidny.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2czbimdgp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2adbbkcux.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2weprhqbe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2itxpzewt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sipokyud.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxflihv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqyunt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2spiyxkie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvxkdnh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnvgaia.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhangp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvluunu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2cezaysic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdkndhi.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2spnnmvjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvqionj.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2grrbxbuq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqiaobz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiezyxs.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiwytlv.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2tygupmue.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggflswmm.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuuifmu.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2grwygyep.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdcgsdp.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhsmily.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvidoesu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmnnuvw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgcdgzj.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udyksauf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwalkpsx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2domjuaxc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvnyyvz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcratjl.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdsjlng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2waavfeno.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsvpvcb.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozawcgkh.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfccits.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjausbe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2flmfzcmc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcypebq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrqsglc.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oghdelnb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzdpiog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujavmmxv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2imripchf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtqsjzt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpidoavf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kboocxzs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwuvuof.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2cddgqhey.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfscgko.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuumapg.html


<!-- 参考信息 -->