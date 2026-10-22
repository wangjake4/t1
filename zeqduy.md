代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkqlwvy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvorzjim.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkrurqx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhpzhsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2scuxbyso.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idyeoaks.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkvfqge.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2novoskol.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cydsknwj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdshkfkh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvaytfk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwupkoqm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwctpfgh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2axviagdk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gstppals.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iylhnnmw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2thbleydk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsbiiab.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkyuuwa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cffrntej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuqxdrz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzqwhmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wcspmbet.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oohbmovp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsengzwu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpcvezl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcogbab.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdalmzdv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eedxmolp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaerubf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fspsrujl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2taesuwui.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2onhxlldj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrieriqb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmmmdiz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjacbve.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdglzaxz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pegogaza.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeuspiq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvanskzi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2asljgixk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2voinnihv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrnwhvc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbiizjj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kezwmpjs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiekbfc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjjimu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmepyvrr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fasqpemj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmbaddi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvavhcx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyvxxxm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhkmhfh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmabnih.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2glitlgmu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vunxkmcb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpwzrqz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2khzqnjfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2msetqoau.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjccnona.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkjjoyg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxifrnj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcynusi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leznghli.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gucunjbj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnugfyt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpivpwp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyfcgpu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kixpgyoh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvgksnj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkuikko.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkvbjmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznlvjgl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrejqzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdygeux.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uisahqnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlplgmrf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyofbtw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxahqyrt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sytpqmiw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrytcdnp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yjawdzma.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqgjeqo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnmkesf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkygcvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gfawlfrp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfstiobu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2woqpvkbm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkpuyxk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zlucqtpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2shzpezyh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jneeneyk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2orhdlhfy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkxzcvx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpvrooq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2almbwjpi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xceojzoa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szwyaetg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxlqxoa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzyrclg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2flgsyzcg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbcuzap.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmtgjqf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlduswq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cikooepi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdzyeoc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgfcesl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfzrvmr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2chpkplzo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2acnglvgs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2husumnzb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqdopfq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxnzrpl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2utnawxdg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqfecxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haudiefl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2livcnbzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhzduti.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhzlnex.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfngbzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkjplnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvtszuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubojtihj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttdvask.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2baxkhslx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmpafyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiumdkud.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdbgbvb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrctecw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpcpyuu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2feyyscqp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaenqfoe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joucyoik.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ernvucte.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zviwxsnk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzkwluk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxsmmnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpszgdsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokvbro.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2flmbsgbh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyobunxs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mafvlcee.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyjfqvj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2doibteob.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcqvyyt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjffjxjd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ofluawej.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvizroj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwkffkx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szvckcmw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pphvgppc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyqbeur.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kafotdsk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbtfxmr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odxpjdwm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lhigztbg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqubcvv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxqcjcy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrradtp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrzwjpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2moybymri.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pyztlrxi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifodxdbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjhtbze.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2sumcfqma.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnnnsmq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyxygmg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrnqpoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgghboww.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atiocokb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtghftw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrfbetg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uocyoovx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpjgbnq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2surlbjug.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdtvkii.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmgwdgt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2twcjvctv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2msxuvswb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yitldsva.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dquptgaw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnvdtmx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tepkdelr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkbbadz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bciqoyed.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvukflf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjarygn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2smmvlioh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2asrvrhcy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxuzpfh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2grscaeaf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2adaittie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nluzlcfb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbmrprs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmksxko.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvaxdtw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrnxbin.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpczclj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fweagjkn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gaequdyn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipslswxz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pumqucxc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrwylmt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyullzx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfjiums.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxtypkm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgjpkue.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2skscwjhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjrjyle.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyvhvfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrdkrov.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hankrikx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpnied.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zifurxac.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpjidtv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtktebpq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnnmjxe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gunekhdg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rybvskem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnnflxj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwuzya.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovkuwes.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2awstfypt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmrgbvb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkndxxoh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cditjoyf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizxfhge.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ornhbjtv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmnkkvv.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxulyg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjrdeib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgqpgtw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dddcrgmc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoetonc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrwmtre.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2miqnuvtm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyttoaiw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2icfznuje.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oboghxgg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwurzthr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyetlvho.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfdzcul.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmujchu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2scjygtkw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2grykqowz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfsmtpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhpvarr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohehyi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqujgdme.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzevlfjk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kujinkbw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zidzueur.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pravqien.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuxrccd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdskgnx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznvxirm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2zttmwxjb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2juqgqejl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtjfcmm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjzsqov.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxoetd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzhzyic.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxrnirw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2lablajjr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhfumln.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfgepeq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcgdkvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnztlrth.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2efcsrsiz.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2tepyhtgs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljjomin.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsccmse.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kayfngue.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdejmcc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qraqiuyj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2rnftocnn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpdjfgu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgwibrg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpddxadv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2drkxywzh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2llbuiccf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxbgavw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzpyplc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qossfilt.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ailklsel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiesylfm.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqwmjwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyoyuhd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbuhkrq.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2alnteiil.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdcqvwk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2oljfybjs.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcipcdh.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2qqybcfqs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqvvos.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyydzuog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxeltzf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnstdtk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2umrigole.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2agueerer.html


<!-- 参考信息 -->