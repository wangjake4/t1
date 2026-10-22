代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjxcfaw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzuhpu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jejasgeg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvsfllt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwviotu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bllwvewu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2thuobpyp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ychranha.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfistyyo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2norkrhid.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxuwaaa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdkffun.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcksvsxc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nksmcslo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlgfkzn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqlhcu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtnreew.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vswifiqk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctslsrxo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtokidu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjoxvgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2slillybu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rapxciqm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nudsgoev.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qrthylfv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2psiyosqv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqvavyh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsqzkwe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwydupr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jotoegeg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvkmzlt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbthxnf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2itkpredh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2btjaqkou.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgcvprr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2majuhmji.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2poxisfld.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlglgrae.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqoobxe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcvshtk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2twflzsru.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgecbxch.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpqzwlk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2usdjgxgb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bewwltww.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbptxqam.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keugsnid.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kevtfsiu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpuskxr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqykbpnp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tciaintp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktocibyl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzczclg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdimzdz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2caqhfivr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stuikziz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukdqfhn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsedexu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuastatj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lquxplez.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2emuabbnf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqkgjiw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swwqaain.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvsrwct.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwkpcnt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xddreorm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hihlzbzy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxpuzwk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaigsdb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iwggtmbh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcjttrl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdlwaxi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxadblx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdjedvf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwxbfkh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eagevcni.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tjskscfl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclvptzi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjavbye.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfuxqfi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2breaqxax.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfukwoy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfplvyhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuevxpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeoqged.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxcfbyl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwfdex.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aocjscvf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbaszot.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbvguj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jopseiml.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxbfsce.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2raaflnrr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgigisrj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmqzvvc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kiivhfob.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyfefmx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxhinas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkwlul.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxyraba.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvmgfbw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2extsyhyo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglvwqmh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyywrne.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vshabnit.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrmkoem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwowymv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqpihjj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qugiejlw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqyztdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2llznilwt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2oflzmamb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmsutdg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svinrhld.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2phvccvbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2frepwrhn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sysbhofi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlcelcv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxfxjmf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wedvxujq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqtapmr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2elclupna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwlnmlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wektchub.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqegoqqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmacibjt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnpszf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjawvsus.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfiigno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ximkhdiy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxnbpue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjjzmjq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnrgsei.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alryordu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uimprxjy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xruzprgo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdujms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gitjmsam.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2celswbwb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeouawab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czdbafxr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxabsux.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfmmxrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kugmairf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwwmfeo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdvifga.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2haagrylu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtciuuv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyinecm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qecydbiu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbpdsuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2upyufhhe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bemktxhl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bljgtisc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwlnutv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbcblil.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eznkennw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxlamnq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhvwrha.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2heqjpyqq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqtbobh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avbbuekk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upnkqquw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ygccbrjr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqnrglg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iykrkhzt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erxikcmu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sctvjlyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2scakpqnz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbwuaxm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwfoktz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eeulyhwj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2izhtxjna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebccinxo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bemiadek.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qarxyvvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2morbyjom.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfilweg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzzynro.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbpmejk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhznnzqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yinxtbkw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2msgnrggx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvmspar.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjujlg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfhnnlb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xspslwoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfrxppn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitmtmwn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hcttzdjf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2twbinsbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaoqlot.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vxueoaho.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pippjhhj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsclomtb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxxewdo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsqwitc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hoetlbug.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iscgokao.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xerlbsgg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkunwqh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddubdomk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftsdlmp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyactkz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkjcvci.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2otfslubd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiibdwv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjcilne.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2osjqqvqd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2bragpjre.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tnteijis.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpidhaj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmkqodv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2puzwkcpw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmnzols.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwwtqtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdiuzvj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rfncpcen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwmvwsh.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqofeohn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqoiwqn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fptsrqew.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzfiztb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyuamdl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kstscjxj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odnlpdtt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2witpikve.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fignhulm.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwyamud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmalugwa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxillypk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fajqslrw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2crtmevca.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zskguqqc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxqrnsn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygptfnpf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoqaypk.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyosxva.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2infdbcwn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2umktkklj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfvsrjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnyksuz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgocbqry.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxwhktz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxovbmpu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2synxofdh.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fivhlhom.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2johvnoqx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vacyexxd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxogoaql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbrgazs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfqkxnd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2msvziych.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxssago.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrnyslx.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmgaphe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkxlmoc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttlkytw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuystyui.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2auonmstx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoecaii.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjfglea.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swomrzuc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkmwdtm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwakrqgh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2onnvlbsu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbalnxfh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kheihcef.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2puohhjlq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcriov.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2unnxqujc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcrvekz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyvuywr.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kihvzwkw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulecsmmw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ininqtrv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgrzhvu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzgxers.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrbwgke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiismya.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vldpicpf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcovpsal.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmqhajr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzhteow.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2srabiqzv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyrtvjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxjtrjk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoaefma.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2rgalnvwb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzypkbhk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2narucror.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osakotps.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2arrrajoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuyehlr.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lxubchci.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhqxkhm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2juyeblqg.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2amvmhhka.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgcjark.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqhizv.html


<!-- 参考信息 -->