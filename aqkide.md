代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyqvtqx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjqbolo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxreppi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjjknzt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjrbgfc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpujlpbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acwkzpzu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obtnhnlb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyemdno.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhflah.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbaysas.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpektvo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2llynffim.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnkfhky.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lipmnjrf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdviphw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjggeqgv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoxtfog.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvzduir.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vretrfeo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsfitik.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcimtsd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjyjvs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkkxkps.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiofhcgd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxylarti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjyohyw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emiaqanb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rielhtcw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwribfez.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgbatfo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuggrgt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2poplxrrl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgodtev.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2byzltbis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbejmjeo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vpllrozm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnxutzi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2orhnksle.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nywwrzmh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgshbte.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clocfzmo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utxzvalk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoxrylh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zcijmaud.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdlmdcq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdfhfog.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2clxxnbgv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jpegxctw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slysyzpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiucavw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkinlqns.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uimuqiub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyikzssy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nntfpsvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbvzagx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmpmkkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkmctxx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyrmecf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzlgbmo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfntrzs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tspujksd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpvqhfg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzagnyz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwxtjqu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eakmppyv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bicmcrwx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfcdron.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyslyil.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2menkthsq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkqplef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyibrquo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpunbkn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvxohav.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdutkrk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aafrachj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvpspax.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edmfrnlr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzsoapx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pscvmism.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovwcdtd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqpqlpj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhjrfd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elbpwyqo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdeqnyi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vugfpyqw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvqigxh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ychugftx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuzkpfi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdfpjdz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtiiflj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkuesj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtbafsb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2foinbkxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2buwoiulo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyxlddz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqmjlyv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxknpwc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqfrtnb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyhbudn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kulqyflc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dnynqfrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrshfpj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jogboizs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2smkxhogf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzwxcpm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtxxfkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjniuwsb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xbljrosd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtgrzup.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xcprhqnj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzkzzah.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyycibh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fejkqput.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrzecjl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nteabutu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmumvcl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kduaahxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wkonjziz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tllyvfcw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnddtoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrcirlh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2stzkcfqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywfutze.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhylomqa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhgmbvi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaedsctc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskuairl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acqdxluz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izbczguh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxxkesc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmdrrdm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkhuhfm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvromdr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpefjnuy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxkvemv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjinnomd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wcszsxqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqcrwvp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kukhqbwz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjgdnmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfhdhw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxvlnhp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jajfdwem.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2soetwdvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyvobax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqasbol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hudgfrri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dakomegp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdpfknn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ovijkqwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcyzcvh.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pglbieuj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fychegov.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgibsid.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchdvvyt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvekxsv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqitoyod.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpylzrce.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2anydhklu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttohospy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyzwryl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nndjhlsb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjwnunm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnsvare.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbehclf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmwzpvs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzqultv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkubswm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdscaaji.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zmffkoue.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rvflwhrf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlttfrix.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nraschtv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhylvxbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvcocln.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nlajebnq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2klyyijka.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxzqzww.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sknymlqt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmksxun.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhepubz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2viaxskyj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjrflvg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2beowuxsj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hywcfdfa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaoenbi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2aliofxke.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyyooby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsawzoc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2eysikyat.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2clsaigyj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhddvrg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2swnyevol.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txooxapp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2evmoslcx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkskqck.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubwngx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2emscytnj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsmebpm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdkyxyt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdpookx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtzwqpq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoydkmw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqnrnzx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2finaedpr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2olxengka.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqlxftu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgetafz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzizamnw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdniapfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lilbhibv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cubjzbwd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mukkqcov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weogrsfn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2whjcoqnr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaqsyog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbkugji.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddceapqy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjzhrfg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2nglcdnkb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mblnrntr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cadewrig.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crmecpiv.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgwvbqt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlvxweq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xscczskm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eanelvyq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jakmzhcw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwulvzn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnifajaw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2blhvyqls.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2elkdtllw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgacqge.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kazlchpv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqupablh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcohzuzw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbutcgh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbcdrvh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kxitbpuk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmmspap.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqltuin.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dwopakng.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgensmzc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrzyvpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2himdjgzr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bohbicrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nocwwsqa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvulvj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaflvpez.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpfdunm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2skhksmly.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hylgodlw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbebiudq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcqbccc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxlvast.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdrcnqp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhvloij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeprqrse.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzouchos.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2djvldynq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoeohgz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbejriuc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpegrr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2llztfxuu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeosugi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2cnptuudy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwgzirb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlddprko.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiyylsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxxlfxo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwgaxhp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2semasaba.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbkabwk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqwyndt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeetebv.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlyxfpi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhpufgm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2amqatqbb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbscrwz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2scrctewa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wplajmhl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdhhfcd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2whadtznz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2swqdhhst.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwxafkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwupvhpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrsnflf.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2soljbdcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyqrecv.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2stgmphix.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxmvoxm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyausdx.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwolbucg.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2odsnlkab.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2odgvkkor.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qydhrnya.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2sudwbqea.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2awdxexxs.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxyxvlq.html


<!-- 参考信息 -->