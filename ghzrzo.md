代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwcamd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfjsber.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcaydar.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmddpca.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlngvls.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwvkszl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmfcvvx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fklxptro.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfwtsxi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2celjponn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxevfiq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phqgmncy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmymho.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrrovtu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bastuerb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgploux.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jijslmeo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvjffga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abavdvfs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2degjzoyz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvwjhmw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrtycen.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdekvu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mebfzkgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpjpcog.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmkjlnn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2owishhkf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyyokur.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpckhkre.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtmiqyn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeeryta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfbskm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwgsmns.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2adtdiqti.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sstizvjd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2suywuypl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tittnlzt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaodzkb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skelcwwp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqhnprh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqfzunm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2syisnxcl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igzhwwpp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmayhhpg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgqgre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxitwmjc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2roihuqio.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjctqije.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpswejx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgxowxz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqpows.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edopklxv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhgcfn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqirutdp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvzgxmh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnyjysz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpfqrhx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nhczuxom.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jllvxpao.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdxrvaf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtyncjc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqvvsmv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xwliwiez.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyjghjs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heuqztmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpvdvvj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jotmecix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgyhoai.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlvdvod.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtacxxxv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnerlpc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzowujj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwgryie.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxpevo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhpklzx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luedzogu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcegluer.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqbglud.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrmyrvo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gymdpnys.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmwriyi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qzznzgdq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kyucxrxb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavppzp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdfkrvt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvsejkx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlkjric.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eokyjzyx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrjtaif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oroycdxe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oldgakhh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uykyclnk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2siqguwij.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfokadgs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemtzreg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqefzsm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeihnlz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dakmeiuu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxrldom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdenfux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbotiik.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyhwjgo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oevumowk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuzshyj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnxqqxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwnkelz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuhrpsb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yyetjfam.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfddwlca.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvqbpgt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2opjsbbdm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2knnlkbib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rihslblv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfgpyyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqtlik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnnqvnz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckewagvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwkwpku.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ueptenai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqdlrdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuythwm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtobqob.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mluatkkv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsazfhjz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dsccuggu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odrdyqxt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokebpuz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqibcyw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxkxylf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbloxbdb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtveizq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysoptaa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzfifmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvbcwip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqaamva.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anfunjpr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pjallbun.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2djadjwsn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwvtbxa.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgjlge.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bizuivcs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcgmcbv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzmmyvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkgiloe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkibdqg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrszvon.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzdpezy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmnvmmy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiqjeqi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dczksczn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpcukua.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohizgjs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odqwtybo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edwidypt.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otmflskf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eysyganj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxgoweb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoqqcsw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcldagx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbtrqrk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzobeal.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhudwus.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehembbyo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bankqqrh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2asoxgsfr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxjslyl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdafuwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjqdwbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhczpfc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szcjvcbk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqreqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2khnrmdro.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqrdufy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptcfav.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nclqxqqs.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhedkhgq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tutoimni.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2urppmurv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhpkpsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzikdn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2spsfwzbw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vzistywe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ystthoje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2badezppb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2htjniroy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2muhdktvo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnjnijv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvamdjs.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvrkzje.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2koqagepw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwfmdoq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqivfyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfkjbo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfxomub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefarto.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pevbmnew.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pocudgjp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjmeutr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hcskhsab.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kdotyiod.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckumajfi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnvzpjw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2itzyrvtz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwtspyx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbgyvis.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqreubup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwvwaaa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bphilcha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fulfzbbw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gankixin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoooekf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbkhnbd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuifsape.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lobnxgaq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvfaxvg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oawibdww.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaclfvxp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoucbnz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sonohedx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciemuulx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2smrilwyz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vssugbti.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwidjol.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2endggvek.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oanzgscb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnmjeyk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvyauiz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuftezs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yacrqthp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qypgwtvw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lipevczo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnenztb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ectjkubz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnudhu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvevxdp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2inclgjlu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoffdxj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnympcl.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtborud.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjumumbp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuobvkj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqdekra.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhzzkvt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vetgsjmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2edhfbjym.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2enxjdsic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpshsjyu.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgdygqp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jovsclby.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhspkgb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgfjxhd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnigjhf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkxltar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbinqvpt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzrmkod.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhyivpv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpueipwp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbqcyiv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2asxqckqy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2weenslxh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ygitmfgc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwibzqcz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpamuss.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgtlfcq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjjhqdg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkyqnku.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzcrlwl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqpzahq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvybfbe.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xktzarrw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupdflje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2twkfbosp.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoabnocv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxkswer.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tngtcuei.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcuffnq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrlvnoc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldsjhoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnvbdlb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2baqgwoan.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2joudvbze.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqtihqt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnpccqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyacbxti.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuvwoiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoprbil.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oegnvsxx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoprqhd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyusobsl.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgsaqzr.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdagqym.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2zstyzgyv.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzfkedi.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsrtuen.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2rukorbfl.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2slptspng.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuudulr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2mczsyzlu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2uknewzim.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdazcvgc.html


<!-- 参考信息 -->