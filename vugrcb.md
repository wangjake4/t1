代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zehpemdc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbujbzm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eouacsly.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjhhyw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnadgft.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wglbujtg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkybatwn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcbvcjq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eacyfkpy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goufzxvi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzvdsfp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2steruizg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2miesqufr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2frpuqgxo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxonvtbq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmgvfti.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpopiyie.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjaezw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcujpydw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vefeijbn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqyakju.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpsmtmk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2scjnwgzn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2omdsldpw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpsqlck.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpzlztb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaepqkc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmbiqvu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjldtkmc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2onazcfoa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koqmtovs.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyexukd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qnntvtig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwzvujh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iihgzvky.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qabgelov.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypijfguy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlbzjoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbimcphl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailpudhz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pavkqtxj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2attuhyjx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2romcwstn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uoohzmjh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzcjpde.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmtmsyt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vwixhccz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yolbmzkn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiddpll.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hokwmpbz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2imrsdqlx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiwidoj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liguamhu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxpvgga.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maorprhb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaqddnv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2klrzvirg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefqgbw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inckeyxx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrbynzy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzliste.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygvauti.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmikmai.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtzhpvj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjralae.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqimxxx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjsjgem.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyynetb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmiwdn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nznuzesm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzwgjdy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mnowuldv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gieebjtc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aswhlsct.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabbstlu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wpapotac.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpnijpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zafaiquw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhcnbix.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlvallk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2medcxrdg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvjpyke.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngvyxjx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaejmiv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2euscocih.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fzepzbqj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sngbqria.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeexmon.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nwegrqcn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqksocx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dugssiuz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnnanwp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgppjbo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqrvmyy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbqozb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgucqwt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhfllcd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicuaaeo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajpeqny.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjckuml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aurzkxnu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gacyfanl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gklfpusu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgzbgjn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcveptaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shvcwqxp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdiwrsb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjwrjyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwxsmln.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2semsyxrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kliuxzob.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcmoepd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2okvgmqfw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2veuniwwz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmofbsi.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2trbxlhuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuipdapl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egbhsgwa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqrvqed.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcjovlw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bietswmi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcptfnwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeaonae.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2laktffrf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzkabnu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsuxiii.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmzjvbu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2esysnnek.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbncwgkz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rccgaorr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nppngxsb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gudkpkin.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjkitmb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2buhbnopk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbzlcwy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exgwfmgy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rohbhkao.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igedvdmg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epfqurfx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rppmeyll.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmrtzmi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srjzsean.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnvxzte.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgvbno.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zafnzebf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpyqdkn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsneafj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvlmzsr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxrpwlr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhhqlnk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtifjvai.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkxckxi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyoxntl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsvgfrd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdwxrxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2khamvzwp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmxowue.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xurkyxpi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwpurhe.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2atcvbxad.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qauqtjsl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwyhmrv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jesczutr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlrokzo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oodfetqa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwmvub.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eidaidjr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sltyojst.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpjamac.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzkcewj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nasmrmok.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2szoddboy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qeelwpgl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgnrugp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rivdxvtj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mykbjady.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrssgno.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yehuutrf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajymbhdw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvzdojk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmfukbs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hieyaser.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgligluh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eybtnyek.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pspaihjl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpbgpsc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgdgcbt.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnlaqt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2quthxpzy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfkxyny.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hojbvkar.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaezsgi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdblbpg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoowcfi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2nezywfsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxdjxmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crnmzswk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbemtoao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnjhicn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpamxcee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpenkpg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmobvd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaanyjo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fprsduyx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiqoiqy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmabjzks.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugtyhck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmixico.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwoaimz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavtlibg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhhowzn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cheoufla.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2axftdybi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrycnnp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfakoivi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfcnvor.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckfwmj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtjhuyp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwdnmot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2neojzkei.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cbudodfx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgkfsyc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvfryph.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2yksuiiom.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wslezjsj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wcliwpni.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjfxza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2czgwlgcf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpjnzqh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2saavxach.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2npxgosls.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaezeum.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tokazvsw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsffgtii.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzpnrvh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqrbhlu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwirqdwp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxojyag.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjjcxws.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfhdism.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2asjmqumh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muzxqvyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgizcio.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2oghwifgb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyhtcri.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwjkfpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2dycvcnvr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmpovqs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnutnzp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzadaytr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzbluyc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvulpeq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2licphygb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsjfgbh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljviaho.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapqgqt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2fufwupsc.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2odijntrs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyhjkqb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxhegbg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyrqfki.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2toygswfk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdpyvni.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2raklcamu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pojgberf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2csaiayfo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcjhfwy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdkeyro.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwxyewv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtcsuyv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjsbqjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sypzvhwp.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaijphw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdksobum.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iodzxkba.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkulgfhz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueirfgua.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxgkdiz.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2enxbzdvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hriafmyj.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfskqyfx.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2dcowjofl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvahvnb.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzptfsgx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2eomloalh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2idsuacih.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyautfk.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyijacgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnxtcry.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzfyben.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhnmzpc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaujxtx.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrjrmta.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpeumnf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeywdttp.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mayoiqzz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfbjwvb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvygnphi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2auxudslf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zterpzpi.html


<!-- 参考信息 -->