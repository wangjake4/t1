代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcuchxb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzczsfk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nntycpns.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhrxykb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sccdulyq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsqjqkq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjsmwyf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpqhezq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2saytsrmr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkofdguh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxipqqn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2slxqwlws.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ygneghzb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjzholt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyftgfbk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgumcgap.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svahhzee.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwgbokq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rymzgmxa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkymtext.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyivoul.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydalkavw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjeffod.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsadtgj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmngfzzj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziibisig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoipjwc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yngcyjth.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxrbyin.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgadzec.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2napjkvsr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbujhblj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqcnwse.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiqyvjz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtgcsjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ksujgsuc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2emgevkve.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxrlbd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urgblpso.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvcsai.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yilrmean.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olcfsmlq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdkufyn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzwkkgp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsgqbkf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqhswep.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bukojnzc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfzzoke.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aurhhgot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypmexor.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ftndsjqh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckigwmhn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqizyizp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjqjwjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epdjpcha.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalqlvac.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gjetwjsg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxetjha.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mgshejty.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2swavwsoc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfxllvv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rahnqhar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrqrjlk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwthsai.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuknlvi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jigtoiat.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlbngso.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhllbzo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioejxavt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baarxtdx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuthudd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2coctngpy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hhekbkod.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvzzzwg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxclegl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nsipuopm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owkifnjb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppkvekj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprwvcnm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxnsfqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2farhodha.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2koycvdyg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzbukvk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhprysg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgnmssg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpjkwrq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtlyrgd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vunxsmen.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlnnfuz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bengoqbv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvvcane.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcgwcib.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgqhnnh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gicgbkle.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzmvdts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2auylfdmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbgonuj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pntkvaho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjqhikq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2chkjqfot.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuzkasy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgimppf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfpwabe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfoczx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ondfahru.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjvhfff.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrswsit.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwywvye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhiefcw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2snzmszws.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbtqocw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcfagbv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehssqszs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqxaxwq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpxrmvj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfgcliw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2njdgvbsp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsppxgs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2koemulbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfghvca.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpntzkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmdrium.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2midlzedy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fchqqmts.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vclyjdfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhuwdfm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzrolmd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnatqsdb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dziqxorq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kedfprwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwgrzpx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lsylfoag.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfzmgzm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgtfory.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtdtijh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cciszpbc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipojnhtg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmuyyxg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpuvfqn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thwuuyuj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfvdscb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2piegajhu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpfmrpw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnokmhmb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdasgrji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnyxnd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyubaim.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxwuwip.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnklitq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfnmgfq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqlsbgd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzuaamj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmvolzr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llaigues.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omproctw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsnrpmv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwndiwg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szkzkhhy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kymdqffq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2onafpzen.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvabehx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxzcpqg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guvuqnnn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2incumokh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrmutec.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xigljkpg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrazlcqw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yynfouar.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cevxcnpz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnmkblr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpicmxf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjmryrp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwvktci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhoxinu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddjacef.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpyvyjs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfhjjaz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmaaijk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2auayrrpw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmqwmyb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnjyrvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtswvrw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwawodfl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmlsssl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuwoqoz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdcuybm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pruwqxgv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbeqqtz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2iiitlzxg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nagrfoil.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2diugdlnn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dktgfnfg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2luwoydyd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kibvahuq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrfhhhv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzolyaz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2feozskfe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2eognizsa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sszqkgjb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sniwmupp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgmhbcl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeegdflb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnzrzal.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfixnph.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2sprmeldp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujevnhqu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgsjqnn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqacbkf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeisdcl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jznvbcsq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrlbnu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqshuac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuqljwb.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pexazavh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqzavlw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkeaxus.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxtcdnc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoadzag.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uegkvbsl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhjgpkl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qursujey.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzxfwkx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxswucul.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgniuyvi.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2khxnnbpa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtpzewb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfptdnxc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdztxmfl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycewllu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xetflirb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtjswia.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpojdtzr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlndvxqg.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sytlffap.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdobxwp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxaexwh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvertmvj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgkbakm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpytsgq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2diklkfmz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2phtjoizy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfplhjz.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izvmzfjx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmscsqu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjistfr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vykrvyoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxrtpay.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfutrkvl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gglihgjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nutrsnsj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiiaoka.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2clgexvxo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpkamya.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zozjssre.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxholkn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingdwnbc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqunkwc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcognagy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkwroaa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2arrvugdr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2leogbjiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyozcmaj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2harggehz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyrcjct.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dppqxcqz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2seusnclm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtrgjui.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2trwlwwgw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaitnnc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjfblpg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsvygsb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhevdbcp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmdtxmx.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkdzbtr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtrxayt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbofaafg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhvapeo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbowmvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjziebrb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2bvalmnlj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkifcrr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgcouxq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkftpbxs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2nezuolsb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2utxdcmsp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilekmnd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzfvedc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlhwjwr.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fobbdmhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwarysmx.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uofkimmw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyypsdzo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzegwfur.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsntowtl.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2brskpcwm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbblxypm.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiprjip.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcaxdmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxwzaun.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wshaabvz.html


<!-- 参考信息 -->