代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhqxonq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdlxuje.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwhrqjw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2knvvmsgv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlhpsrm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksewbc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2useqecpp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuwsrkc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqrewwe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozahbgbj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phaujewq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2szehglis.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrasvat.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkpvjid.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2meiqezul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jssqfkfb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npbqamlx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfehxkio.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkbbwkx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2povciajh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsynfoq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjyloyq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgosibev.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxutwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyiebmg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmhnyym.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpvjnoo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinnkbbq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jojowkej.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptefveux.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjzilhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukvvuow.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsplqmf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hanndpub.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uljbingc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2biwuaeqh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjxpthy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhtjvti.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqyaeki.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dospkqbz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iswckknz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgwnjye.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pybgqirh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sithkeku.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2achqqxdn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjqtbqw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdutrucs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2juoxrczx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnxerbt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgxxqra.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjidvbhy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbzgrbd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqtpel.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoafjqpd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpjhnps.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyftwrj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpemdrlg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuxrxqp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfyupie.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhoiphd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkedrgj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kagpdsvw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xjncbyxh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwfibei.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvqccyg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiljfxv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmlyjvs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vemiysbg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aomierfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2agttbgmx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2izpzkubg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvrzyta.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmadfh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsovrlw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsihfbfh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wluwezym.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qziaycnt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfqutua.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2igxzfuyb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zncnvujv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubqica.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aawrudpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavhywsl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcyosnq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2aryeczaa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyeahhn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqpghh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyfghpn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2upitrjgl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgpmup.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2epeaahfd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaxnzaw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2atxvcpzr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2biivgekw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkkkrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnjipq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bbealpoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2litvrfrg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyoaudr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqhecnd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgwotow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudjoenr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkcbbeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdxzzsi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2irqblrth.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvarmeds.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujqtwqj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mreafbxu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoaszwn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoojfva.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzfwqcf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkpwuix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhquvkon.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvsasyw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoqnkeb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzbqtop.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mjknplwa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pndebnjs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vafqqhut.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wndgrdrh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iohiafpj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxuqzb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygmxppa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbfmgmj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkoiumx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkqxwg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eyysgoew.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpjbxaw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udhftbds.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxxdsaw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2radlncbn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhalmv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puasnwvc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwlpjnz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hezzyxdf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsuglmw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuoiuio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqstyip.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xofyoxcu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lljfyggo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vclbkrea.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2itmrmbel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onjotjsy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qakluchb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzmokdl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjguuus.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcssdzi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzufhpo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2leekknok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xguughpg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdgbqun.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2coozksna.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tutnptrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjalod.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgtvegj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eanvzfyl.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfhoejz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcwqbkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdiscxr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzbwcrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oolszrrn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2inevqfsk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2swsaslyb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2subqutlg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2otqxjonf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmtguqo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbgfqpp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fecxvuja.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkfidop.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsezusi.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvmbfwq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tccmxjie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqudsuzp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmuswwe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuofshk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkofekk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwkfuk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgmmzbs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2addlsdpw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnckldo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnelwghx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nldbthks.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfobtgq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjjnrvk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmdmixv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyfmnwj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsqstaj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2toinrtui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbnkzwi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvpelcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfykzta.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yaygdswt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etxptdym.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2laovdjle.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgjwjtz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2emsrsobx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbbulkg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdjopdt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2objxfodc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlmkblw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tgulxcwp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsuqegf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvlmwrw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jivabagg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfewpdl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2enfmfbnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dihptlyh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaxnsfq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwjanzp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nydzppeh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxtprpq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zceepqim.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkvldgh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiccteg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2axgufiwq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnqtozu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeheqeh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yosmgsxd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqndhcfi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvtydj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vssbyjui.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaoytfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsafzjcf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcodaikg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkgskxi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvtdmud.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxognuq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gypnnldl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpvzlw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgimcwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxuaglr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wquwbcyz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2slubhizf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflmfmwo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnipweqs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2uupttvcz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2aodqsykj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuukvrde.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqsynxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jwarcxqf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2hoonyazx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzzejvz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtnwqwk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlyavtx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiwaemv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqfvaph.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgenxnzr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpxdeic.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2usnlripf.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2oivherlg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2besqivsn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2emzfqehc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlwlyym.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2kohtgxnr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbjiewd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2nreziysd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuucwhdm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hedpycbf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljtlcar.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmehocz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2npnqfedh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvajoayf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjnkdkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2virtrojo.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxhcvgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzijrnc.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ydafeqaa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckxkqvz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcjwusr.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpvlexy.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggissrft.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyurims.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2awcargbc.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2xjedsdtu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2imolrgpn.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nygqlqvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2myreglah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2nptcgpwn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrdxbo.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2blzjtebz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2xrybuith.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2zqazmzgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxvdgsf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2abxiacab.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ssanlriu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmymwkg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2snoqxaqz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2xemcfxai.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjcfxkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfxkaka.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgbivv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqdrgxa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibyjdpk.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2javmwpva.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiydaxg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzitnrcv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqlnqae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifbind.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmgendt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwzxlyo.html


<!-- 参考信息 -->