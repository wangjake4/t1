代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2weserozs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtookins.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpeuckk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gahpafpo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjjxxmf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymajslbz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jldrxxad.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exlkugwd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtdkbkl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqvuemh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcefdck.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzrtkqk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oembzxyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxdryfv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2edjwkxkh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkwyysn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2impdhwci.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrkmovw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwnqnlg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsafrmh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2klqzmeut.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xplskoxp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fedmtsfu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxlzjbd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2epjjhaxk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvarxxhi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnzmkbb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwyuqfv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumumcx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwllakq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixriohhq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sabvayzv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rgusggoc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaxxros.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agkwnlqq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2toatxfnr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cithcdag.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwnexbg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2icdbrxlq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohxwftq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeqvkyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvdrzae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gesqmgor.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlanmukv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvxdihn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoovvdoq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oabhgbef.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxinnzr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmypvbg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ewralxfl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmanxrh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2heamaetl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqmnmld.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xeynmmpe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dchcgbti.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcigblq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnwfcpm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmzsrbm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgvgok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvutcutm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tgacxgjb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshscjxv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zeohqbkn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2elonotww.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrydsoi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2larukzgh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsozsdi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewcxnwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhqzbwa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmtrljx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcvakdo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szinamoy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqtsngo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuppkzn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoykszp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcgifki.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lnizcrfy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbbbnnr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndyggmk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjqejxk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqpxafx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaleazn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktqoyu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2igcgkywq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtauucz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neehqwrk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qflhcgeu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpawnvx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwdvlr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2duhfbvrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqbdnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqonpqtk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2unudawtb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkutounm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqegydb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibrszhh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yepibgdo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtwsaiq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvzulyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dstaofzw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuminij.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsfxqdn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvvuibi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpqkvw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkvwwqg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2erflztvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmfpifx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdehknye.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiwlxdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjicoq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrfoofa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptvndrx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqpkfwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxiqwfp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfgrcoa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqxvtf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pneudrpe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlompna.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iazjvscf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2stvqoknp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcbdnug.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ickbwxjp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgishod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueptrtdi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2daeanjsu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujytelvn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owozvbma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgeocm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsmhbar.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rntdovrd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2egtogsxj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnyvhtq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2csnkfazz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2itlqhykp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwboexr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkakwuky.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmvycts.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htumjrds.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2imyqchiy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqvngnl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbutfnhn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrcogtl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqrdic.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfordml.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrfaiya.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrshxxsm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shckmzcw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmzmdvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdobyxv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnogjdne.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdldsg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xktchphy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkdfmvt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uruujnzl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hffymklr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrjzcia.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdclmpa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2okvetgbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yqssoete.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2svuneafm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfkrwvi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiivfwd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2folhwumg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmblgvz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kpacipty.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2swgvvuee.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdmpzrr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqcrkol.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmwfhcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjmspr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkkbouy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2impwivnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydopsqm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoempll.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jybyhiyc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2odlorofq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mupjqlbe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlcdwvh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2maunpoxe.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uanbxqrj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqwpff.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyatbwn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkpshjc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ucggadgf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrajcsf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyddjzwl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwpxjtq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbkzwdi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2idhlarwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfmhere.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2weiepbax.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hovvjzng.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahewsnox.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoocunn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfpgpli.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mzshwsjv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2atvlgymn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjctvscp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygagnzz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdnznf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apddupuh.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uilwvpev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zteinein.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mahfeoql.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2idacrzfa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rteitlmy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qajshnmv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrvxior.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qphcouuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqyasiy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyenusa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcefcdto.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywbbfn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctkbpf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkekrds.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2izejkdnw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxalwodm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyfdmfg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sowtagan.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2addlvsbz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdzrzyx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmqigeq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxziknng.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuvwrfi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2glhtpqgf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivunxovl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaofsol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfxfall.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjxxukb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdqlghb.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njdrajcq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuqlthb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbzjmwb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmhmkch.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dldazlfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdppnd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhvoaqr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmcnvnp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mscrkbxd.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjxeol.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynodhman.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpfaarn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcpgwhx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjehsnqn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivgfcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asfwuomo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2prlujwwk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2srxdxrmg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkybaste.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpumjsrl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvqwehr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcnlwrg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsdrivp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdgrxag.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2turofqyp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2hpioiyuc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpglggdo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2chbhfmcu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwytcnf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkdrzzd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnahwsmu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqtafsn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbtglrv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnefanp.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpkbtll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrbizub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swdpmytx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzioukw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlosyxo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2okosbsyl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgvgcgg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zivumkdn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2zkewiege.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqunhty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdvgoob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhttuem.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sigeudtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dykqrsbq.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnezycha.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqanfluj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2huwgjwpk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyjhfmk.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2axypltal.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lueusfpq.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvjelnv.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2mmueeubl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmeytww.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrdlmea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqshunyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsruaxbt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpavhlnv.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmmvbvw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2noibtpda.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2afiiincy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojiynsp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2ludnmxpc.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnkzfjg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbvfyqx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2edwfztmh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhvvklk.html


<!-- 参考信息 -->