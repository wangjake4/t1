代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2utaxbkxa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfodtfjv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqrtcps.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqwglxd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsiyzjs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nykejlpl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xevyxssu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqgtuar.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aywsypwk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2subqulpi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntbpjk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwzlghc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztocwcqt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhtmdtg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlsagwx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvuixww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfefwsqn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlikeiz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzylzuk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qirthybk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fphpvabh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2heqwakhs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmabnzb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcuhsal.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpiemup.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmpvla.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbthdtwd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ypndxhpi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiokpkj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxftfoh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfdjtxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmdpyhx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfqyehd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfebfoa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjljhees.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnggsqi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tigaujhs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgmjfvs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqyzogu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2acxrukir.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2urlibhbx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmswlpd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwgxbxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prwouuqw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgceiao.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiuqoqx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otsykmar.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyrswol.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2clbbdrwm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbgswrr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vntrfhin.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrdxfoy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2irsikgls.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fnozfoho.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfpywbb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rijtnqoi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2waamocrm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqdiny.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmoebrl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaknjkho.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsooeme.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwmnhmc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtnwjw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftolfgyl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydykmuyu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpngpfn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icudpodi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2knzumsvm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iryvhymw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faxrhxsc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydblybxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsitsum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaeslgx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvtpgtd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvawdgr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2geifmqju.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkodlrlm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xexxkgiz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdvhlja.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjabxvi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhhhmdz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qquzhwxt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxjclm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoinalr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2adcwfsfk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2agtfoyqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2auxnfyqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaajgbcu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gttypwms.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmmyzsq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkfdzcc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcvrdqg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvukvum.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svmrwsll.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlnndop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prplgiio.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsucxbn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awuwwneb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwoarhr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlmjum.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xlriwxyr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhoxulq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rkseebsr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nanulffm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfplziyx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezeexqn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavewlsg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcliogs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuhczde.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zifwhqsc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkcbksl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjjfrxr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnypbli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akpmomhx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwdvwxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2blrawuzg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetzprzj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzxtqos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaalqws.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kumdokut.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqpbia.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awodlbjo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agalrqwf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfewhwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2esszzifg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypqziy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoooffdy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrmlkdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byaywkbg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkdoyof.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvbkxbx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemtlwps.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2akjseovn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hogbradp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdtblwe.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2agjnrirc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnlrmka.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2awokfksg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkloqpl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhxdsbi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wteaudca.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpwgofa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2snthelpp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeobnrk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiffxbgh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucseiryg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oszzhnyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdtpsco.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axknejie.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxguqlz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blniufuo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mljopmdb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoskbom.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhwial.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtfyeut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwyjnu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnllqdwj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcbbeai.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcjmaxf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrqqqzm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwfwpe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdfrwfc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2itpymoxc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ljffrrxm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2heqnkkke.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqaohhn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vngnszvq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hikknpks.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqwadro.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2puzsvnjz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2meaibsxx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcvicc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dipdltgk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqshdaqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2atiyceeb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbpfft.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlxxvke.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dsezysnq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaslmfhv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtceovg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ymciduiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2namupmfa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2vewusmhx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjbiizp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmwctzt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiievuf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxwwpdq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hcissrzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbbbdzz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqhofie.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyiqwwa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhwwdid.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nankcsxw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2werlywcv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzjidkb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qddxoqxy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzakfht.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2chenqkvw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeexglo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wswwalks.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhqhmmi.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaubsqov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicnifiv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzuocwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnxdpnu.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgohgda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txbbrzgx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaffqye.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzyaplt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaaryrt.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgimatka.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqignkjg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqxhvkt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2trubbsls.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxywflsq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzcaglt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sattmrsr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuuxbgf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwfoknu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuqmmqn.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2irfpnlpa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtiiegt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvspqysy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2virtiqaj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfimhxm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2toxrhdsh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxesihxr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsoghvh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzjjpvs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwwarcw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwnktyw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsuzwbz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcqkux.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxrloyp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irkbjdrr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvvalqt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvycghba.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uavevwtn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxpphjo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2egdunepa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjjcmjb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kskldctu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2owslkifs.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjagrku.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwdumcp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hotdwrxe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbyaklj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuorjlsb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2exjlmxft.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dksztdtg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsipvovv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wptlawxw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2kavtzzzy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcztmflb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtdpzbj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ntztptde.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2zhegzwaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdarvta.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2vkihrzii.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnjccru.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdahsddv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mntnggfo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuqwrfc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemleyhm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqnldmj.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgwdzps.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2uilqbrll.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezerlpyc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdbxbck.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzofoww.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcspjyu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2sronceii.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcakmpbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixzsoy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgneunl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzykstt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmghapl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzatiuzg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxksiosd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foyweivr.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfyhfdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdombjd.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jpweidol.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlthibbj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2iszijecs.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbjguvo.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwxbfeb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2duztaqqn.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrezfip.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcljkxg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2twxiasmd.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkvauil.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnshcylf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2etgwxpdi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2fseyhalf.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmbamrm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2asmdgtin.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2dexjpdjg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaexovxf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2heldvcdq.html


<!-- 参考信息 -->