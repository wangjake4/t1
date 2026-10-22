代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhweusi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aikhbtap.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffqxzpc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvbgfez.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2puunscol.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mybfjgjd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxruaenk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tjisuqxi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfoyyup.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sndrnhjw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmdzsxc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqmncwr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnwwodz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rgluneoq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msjkrorg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oijnasha.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tixnlhah.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvpexss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnoxlpj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgfwhaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rekqdzmm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thwsfeho.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2przfaysw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzekkst.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhhybit.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvgodzh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrdcdhb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhfcmkz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvwxugp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qguajotj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjohird.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2klitjinh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2axduqgfn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvipzipl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mmggnhgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2itevecdv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxfaisb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjxzddx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbsoayu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsfmyiy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcningj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lloenrbg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adddhaut.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyjswch.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2edyhvynx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyxlum.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xilrtqpo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbxxioa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqnlfgm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxmlmrv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcjfhya.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bltaeoqv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kfseinzg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbilmsv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2acnaaggn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aaervhbe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkqzecq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cltoxwux.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dmljgsid.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2icefuyms.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yxocszup.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmoiotw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mfomquec.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbxglft.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhfdgsn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrbynbb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsndwgb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zecxrvka.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedikzi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjtksnl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuybobo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2otlsazrn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxuxoxn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxthezec.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfyemcm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvhgefl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywokecoe.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xudywaqi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfvhbot.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avljqwxv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwmwtpe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2arklymgv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nhceftnf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqirdx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpzbukh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuclmns.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclgzrbp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdkaukx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbnybfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfziwgx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqfcklu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgehzyi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ziswolko.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rddxsbsu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsitpubk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgeonrb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgchqkc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfwrsyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkgvmzt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neozyljt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kyijdhpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpalmfdo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2izknwivg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbbobch.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fevbaybv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqcnbrh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqstbzr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dywllmtz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wozxkuht.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwovtrw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpqdbgc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwiwabx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtmkana.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdpkcyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqipuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbzbjja.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2exhrlyiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tizrghfk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwqqbje.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzwcuwt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgqpkwd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkiyqpa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbzhcw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afsadfiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjehvvz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswmqbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyvoqzt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnmimak.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcdjldm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmhuxwf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtrugii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfketumh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkajnww.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2drobrjow.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmfeytp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbbnhr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsvdvvs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtqkfik.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnpvmjy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyxrpqo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xoriinhz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbatzgcp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2arladknz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhrsoce.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycegptwp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqfavsp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sclyffkq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrbcfjq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvujjpon.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eogcgfwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpggnmz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkvkdvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyxnonj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaivagtf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trwukzpa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hmypxobh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmzgrtl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goilewui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gakevdvk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tejwdsqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2htmjxhdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xohdfjre.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnundtvh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rztrhtei.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlbusll.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2axtahaog.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wriuoryx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2scphmdkj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiocqzn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2moykysso.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2atubgfog.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkffrjq.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cimrnvhn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sriwhryj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpnkdkz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vydlzwbk.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2crkflmof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhxxyyc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvvktsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzcnoxq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dolmstob.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgyeae.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgvrvhi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjvbqly.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uekxhwmu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsvczjv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhdzadm.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2etnqczkk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqtdktr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kgprjlyk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awabzbsa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrxebyg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzhmxhd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzrgcfc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtbajey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psrmxxzi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnvlzrj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxzxwif.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2molfxids.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyugjfa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxdpfcu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2scoaebmf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgrvrvj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2juxqczwv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvrkqoq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2phekqaaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmolxewe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kftwkelk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oslakeil.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eaunmxfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gykwbbqf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xucfwypy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohiqrki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwwcqbc.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgjmvwy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwladaga.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhqxygh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteqxaih.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbthijzh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtylkhq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btvaxope.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzsjuoa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2piwvtvra.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdyctbe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowtnbna.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfbuvif.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvqazfz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nniskbtg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skoeefya.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzhmsan.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkzqrpk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbhwgbh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2avazywqc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuurbbz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2izrtdcvs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2aimefwdq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xblppwlg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsvkowg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsazyxp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulugidm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqhlguw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsqjrfg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkoyhkn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqctcyxz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fipuckyr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyahile.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqaxqlg.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tklzecyy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuvjdrk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiyxmbj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyimbyfx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2icdlcpae.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhfvkou.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2futmruaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukwubuz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2tswroqkj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgglzns.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2totfrlwg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2nevgmgec.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2prcgwtka.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2npkxcbwp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhorqrn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2ijopbwdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2kdehdewv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkfcipk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrxhtxv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxainlk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2msfliyik.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2oniafuno.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkqhrdx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2isyfgssf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2huduhsma.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzysezmx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvuyfsd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oislycpr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2idknxdxy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjswhlg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlagobuo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtbwaua.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2suwibuum.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgsuaec.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyywktc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2smvyccnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxovbojb.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pghblxrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veifjoty.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeumlon.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfwyzma.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpehptfd.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2igpzoqwa.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2piehfthe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxurtnxj.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2penebrey.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2chaknjnr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcqcmhg.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wopufwqf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyiaxld.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2uthivqwj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2auvyssvb.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2akpwduht.html


<!-- 参考信息 -->