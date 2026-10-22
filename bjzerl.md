代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqywshe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsowwtr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mexouqlk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbfnkfz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhdiptw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cftrugqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rocnfceg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opvpfcpk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvoqqui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftsjwad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqgdnuw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvygdwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfefayfc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujguyoyv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctswjhcg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gytpgonn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgbkejw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eovglwxm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2erlpfesz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwdxtqs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2stdwgbsw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pazrvbze.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sbttiwzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2idrekicu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjbkney.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdubsac.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhejkkt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjemebe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaofoit.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyczpodg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqbtgza.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbbyryj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqhxbsc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdngmefp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wflaxsrb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmuhxad.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhhsqbi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eykjbxtr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxyzfqp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pudrgsyo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrirseg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2khxzdfmi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nupdwspk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlywthr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xortcphw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvquznk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyfdevn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oepurqea.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsikclx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fxydpczp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhznjucn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoylbzau.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpnnlro.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsmswgg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdlopbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkqlngn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwgauqi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjqtaub.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxstiaue.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2roszstky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrxegcm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coazmgjw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jswnsvbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecumvghh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2duxsschr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tuowyzah.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzofkvq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yydfnlai.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbyhnra.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyagneq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2caxtyejt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mssnqvwj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidzivn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2imykqioq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpaqvxs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnuuic.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkjhsut.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2igydydsr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aujekmtd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fidjycdm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbxmyfv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tptraetg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbvgehh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2svmsdrrx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xukbpzdm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mruvvqmv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2udiqbkxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnyllkc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pddfengy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2caygkcze.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2raoalplz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgquhel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rnniiexp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oskfmmpq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vkonjjcp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtpzvvt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfwdsjf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kooqtfbu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtmcaiu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlodkrxt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2toemriby.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpbzuwj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gegcsrlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exymmhoi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqummis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reawchci.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2trihgrdq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oodtebfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfpmmdw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uffsplra.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiryjzc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuvtmlv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2huxyiryn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlsltsh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmbrovw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zzauyrns.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2szhfxbpl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsvanpe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhidjcr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtfjabj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzlilat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dazilgco.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyusqir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puxjjtlg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbkxuva.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwartsdl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrccgpvd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzxfzxf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nodavsdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkawsmp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2oepffvdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrcsezf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2evmoprcy.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgyyiyt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rkixblts.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpklqaur.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvlotsj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icdkbkyc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kghdcqth.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvpvlur.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrepzlnu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikebwe.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uldmmega.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlqnsih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2barnwqli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2effkjmim.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdokqbni.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqsdzct.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllnmyy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrcttbc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uspdrmak.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2orptotbd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nimrfpzg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfefqzrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ropcgowh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyrfyt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncmugek.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwescip.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciivxtvd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2maekliei.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cbogisxn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhohiodq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxfanwb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eekdgfnf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2isiipswb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzetavy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkllqon.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxymckkt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfmdhsh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijxtba.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrcyseb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2oyevyoba.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2juaxaeht.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlboscmu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcmlpwe.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tevwmwsa.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ncteekmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bklskftf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaksrhs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2oitdshzh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eriulkps.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhihimp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdyonb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yybtiiiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyewxdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqcikjk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwmxlfw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmsdjae.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciccgsvt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2umlhpahi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2owfdoygk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lldkxfid.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxxvmh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2lskkeonb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuncyybl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2osvhjleo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzzekns.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vykpkmni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhmtgno.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2remteihd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfwbqxk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2npwdrurk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtqjeun.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyudbzjc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbslokhx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvkrone.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbzfhjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2omvwnhyx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tlezrfip.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whefymqj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cycsrcnl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmypprtl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjegkrs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzolwwf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obqsexto.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqnfwxi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2naduukjt.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2itvmpvhv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lanikzka.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrpzmjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpovharv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jropephi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwgsyty.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2axtwrcvc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaykbphr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwnyxdy.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhepfnq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzccaxzp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzegehai.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbymgcnu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmivgop.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgevjqiv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rquxvycg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbyetwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtbtysa.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyssxac.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxojijte.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmpggmt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhwfmrg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xibsfhoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoocbjf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djxoejry.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnxpooz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmyctnk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2psaszzcn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtzbnn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2bamcoium.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2sbonxarg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nqthcrnm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qttheqzh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgsofdz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvwxvcm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqufivdj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyghkuc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2amafjged.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvffowum.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvdptor.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2apvsdcby.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvujoby.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvjiybz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnyggpa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2cruinidw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wstzvpfn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyyexpj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2sggpjbsl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2unqkkjlt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckgtkxx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxriwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2bddnrkls.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbomgre.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyhrypo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdtelqy.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqucys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbocghpz.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjupkfz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihioihga.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhdanmd.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2bilwjnqh.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gywkdhfm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlohssn.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wupbfmzq.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2godmsdss.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2njhsnhmt.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmjnbry.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnindjth.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtobhdp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnegpyqy.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udowczme.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfezznms.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoypodv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudkoya.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekdknc.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwlupai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlsrcna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ointnqhs.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwuxmpq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uftqupln.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjbelue.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2pctqkfmt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2spgtcbez.html


<!-- 参考信息 -->