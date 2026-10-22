代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yebthyhm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsorcwj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjytwkc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqjwwm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxbvapo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jijuarhp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxfxeps.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzubgug.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cysruoso.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lspidefg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxzznkj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwymos.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvstfxct.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brckwdrl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjehmgnx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgcjzsu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhwxxud.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2catxbogg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svcoqtpk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2casqapjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ciibxwqq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbdmvmv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2shbldwjq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjzxego.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwivgqk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvimpnsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uezanswz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slskquom.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzikhz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnqtwpq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyqhizj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lphtnrtz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usqbarwd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cubqxaul.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgycmik.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrenkat.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxhfasd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlfjavo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lbotbrsp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soqenpwn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrzpgik.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urplsaxc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochxgxpv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfprsy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwfeisz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfnsdhb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgltrsc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwxkcur.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhsutnw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plqffjys.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzylboeb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtgndcz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lewqrive.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gauwpyxe.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhisyxsp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nptnjowk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizepnxl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxgdzma.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvrptu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bheqfhvg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nxetkuxy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dztcuxdq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehutgac.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2exvawxwa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2swewczth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjhkhnz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hazerurn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2soqjyxvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmqfiqk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjzrojs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2brchgbfa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wmirkteg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvdczf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fffpztie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmouhjzw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oddrjzbb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbkxicb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xprgztsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2opkdfudq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvdypdk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsxhbiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkggbcy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbzbwoe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlprdvm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxwzuet.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwztiir.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgizpwd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqrygcw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcrtbe.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzragdt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqcznnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skeelpxp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpvlsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkonmtlh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrmbbze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzxgizy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdfogro.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiyhxhx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxyvwnr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yemtldlt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwgyxo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aravonrj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgdfoav.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxnjds.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlkvkfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivupawgm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2badtvodp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tywowsje.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaoernm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2otdzzhtq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmldypz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exchpsgb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2owbqsqpj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wulldjpm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqgxkew.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2adczzgwx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdgppof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avqodwma.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwkoisf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqbunwg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjohcpp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlsfckg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvxjaae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mienrago.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onarbqvu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycszxvkg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyczbfk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyhrglh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcvxiow.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oectpltx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhrdwzd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2azbzsadh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eeagqzzx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltklcpza.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xitaucig.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qalbcfjd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2elnjvtad.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hwonbzaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrzyrsm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sntykrxa.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbeqbeh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohvkvm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqztaej.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wirdgkrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2drdzrrku.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyqqaod.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedheiwm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mmezxfxi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhzupjk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlyhtev.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbutmskg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjkybm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsizxbxg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2powtnenl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ywokaxky.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nqberlcc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnpbmeq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgtwgrc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxpdxwr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfjkujp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvcjiqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkodvlwd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuiwsci.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpauwenn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeqbptt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoformk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dultcxee.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzuaolo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjywhtn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkbjuqt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoaykwk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhsyxvq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2svrrokdr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqnlfzw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcvonri.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjvmxqb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqucyedt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdeaosm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2whncjilt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpbzyla.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ljicwuvt.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeazlgc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhcgdpv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmwdrnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrzhawk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuxanhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmufrsl.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtttreja.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaabjxe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhlrgrt.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aebfwbhl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqhqkda.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2odexagpw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggjwkmv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdpufpc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwcomxq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twiypwmn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baxiwldh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uayeurws.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqwzlcx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkumwph.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxkzono.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddpyfoj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pugngtha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsutngq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmesxdyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcptdshk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnecnkli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhscvzaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqepueer.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsxoupp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtqxcir.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wegnbqbg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnvpsky.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzwyptz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgysddh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zacbiank.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmcaunw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2udiaabtr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqxrdsj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2euxpsmcm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2szgsaaak.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyillop.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsencah.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnkheae.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnidizsr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojnxyfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bigptipp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2cniqopav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glcyvrkn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wylivzpc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qghaeewp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjmjmmu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtseswp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwrmrmo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjudxhh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2sqksrweg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwlycyh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqbjwbo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxxmqop.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmijhzn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvptiaq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfgsniy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2lotcggam.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbxtwdu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwmeuiz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpprewmf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoawynt.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueekgjtb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2upewulul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nqicvwzx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2iojzsipl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vffgznyc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfybpsr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvddcczg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahtbej.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtuhdeh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfwjojk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvyjrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xflchdmw.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2byzvaron.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqvltcr.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoaxvop.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2sopuyvuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgevczs.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkcoong.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbenuuu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwrhgiw.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xavkwzol.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2uwijnyhx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2uonbokzq.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjfyomg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssahlqyh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmpvnub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzyobas.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuomtcy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2wluknwvy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpqugyd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlmiott.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2fryfncfb.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2mnooglua.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpultili.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgmfskd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2xknyeejv.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2fayvsdtc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplvtpjh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrvfnjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vauxgwzl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbiqrmn.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxocnnz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsangdcs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlacizn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxskfhas.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2aorbedbf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2detmxwln.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpdfhan.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirlxily.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbsefeo.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhmgskc.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjmjuqz.html


<!-- 参考信息 -->