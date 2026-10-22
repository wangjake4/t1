代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwjzag.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxmiwq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqetxdh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urchpqwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aurtqyzl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oexneelk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2haezsszj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcuxdoo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bazmldgo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odlpvqzc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpnqibd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqadyzih.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjyjyer.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaxysrz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snljyzky.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plzfvszt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpmkrkm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mntoqzot.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbocsvwo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfncgsma.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuckvgs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfllnzvq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdducvz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otohxbeb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqqezvc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uifcbnwd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tepfyoal.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2znbifbmf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrlcqzk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxxlfbx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjythorx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvhjdin.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqblvse.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwtebon.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2saoqyqys.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzuclvf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmistic.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzikhrh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxbnwk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tctgeyqz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwloicg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lletlklq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhamjqig.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nhytmyfh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2djvsrhtd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozgtdan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrywbvo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprejqft.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joutrcau.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlbqlgt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2meoqbabt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnybqezg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbzbkly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjepvu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bflkqmvf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmzcxpx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfjyobp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nsluybwz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kmscrujx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hijtsdiy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzfutnw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyotrco.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fpijwsmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbcohyp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzvbrka.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxcrqxv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opkhaezy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lioinqok.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yodyivjf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqszkobi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tngzdsnd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2umalhbog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icorgumr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfukrjvd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkgzkih.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexcqvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnwrlcr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zssykqbg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyolspc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iovpbbpj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdvybgc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgsksem.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmeffuv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrdzqod.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvcqjxi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pruaxfjb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2riqlrxfm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kumaviey.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mpznjabk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpqpgbq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmsnpfe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoqqiep.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeklmll.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbvbpzz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbldvdsh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2btmhlypd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbauvalc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xotoeber.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbbsmbi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemfphb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfnwsou.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwfbdew.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficngmof.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2grryoevx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcggsw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudmcmyi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkscivb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrnmgii.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2omzutaju.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtttuhq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdjsbcn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnktlgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ugswaknt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlovjzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jcywgwth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyvqvtv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2txrwmdwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djvaqesh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2doyapcxi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwftsdo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsydgnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswaqat.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmsaqyl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuvazhn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2visbrljs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyikctco.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gesogogg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtvtzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2msgybodb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkdsmte.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlthnwb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjefxrcy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvobvtku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqdrcyn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrfsnxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbovlum.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2drdkfqqy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2raimbrfe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxbmhon.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwdtcrc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvbfgix.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpadlxi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzflpm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpbzslu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2krdfygbz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xitxggah.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjqxtaz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnhrbam.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2annhfxme.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvoyitg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvylbjd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzloqgt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtqtqef.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqidsvhj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmfrla.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2obeqcyay.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2maouuwgr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhepgxp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yljfyvhf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abtpsgjj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpochrm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nozcieap.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxrzgtm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfndszf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qczauhvn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2faieloom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaovqgi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgjrtvv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwutda.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2roepwlsy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphaycu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdubjuu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zchghecr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2umqhqyql.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghhraz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyjckhy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdafqbq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrsfnup.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqzpmsq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2riowvxyl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rilrtdjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2giyhcdoy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmlalme.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nffrhuur.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uiksosft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhqbakz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabzwfk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhtieii.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvzbcs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbefnnq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyfgpgm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2quamwlyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouodhtvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxihhlr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2umdolcku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjishltp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvtqppp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2subqdgyg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2plbuosli.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xllnoqmt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgftxvz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvhohya.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtqtepy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdrtnyt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulcmhz.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zufekacb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdvpboj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbfjtow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvgbjn.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2izliwbjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oihosfmr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbvbrud.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcienff.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxiqdgu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsslusz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaegldwb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kywlpcun.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtfvevq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzosftbf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdchjzyw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnebeofj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbklszr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjsfdqm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrojgra.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndlbdbl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwermuol.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowtasex.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyytcrlo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwguxwik.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjqyvao.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odyklykk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjoagdr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eesojfen.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfytpxki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbxvaj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xzupozxm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzozoni.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ommuenjb.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoumbei.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baylbtxl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hijsfhvf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzayrdzi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrkacll.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2psrpolzc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygljrvxc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhroizzs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2usyamzhc.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2akfdtfuk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxsrjve.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zownfynh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmgdspl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2redxasdx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtxcafb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqkpfqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfidrjty.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvqfrof.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2syebhvqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyhuzyz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrgkinf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwfguuc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2evofciix.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xynoclin.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxxfxse.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfafsq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rawnewlg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2humsdcpb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2moforjbo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2lynqiqzq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeokxxy.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2zohqtlji.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2hufgxlkd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2acsnbstx.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2inzkcgqy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbaxkwf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrseyuhi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwqzuyy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlacemhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2okdvjxug.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvtztmh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqmscrx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdsopff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2miqeqotk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfdgtit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fixdsvei.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eryufbtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oulkizaw.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ypguatmg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxumpngi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfhorcd.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2eubechbh.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhwpggf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyyzkbm.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurmxse.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2lktxhevn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kznrnani.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoqbmfl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtfgoob.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2usmshmhr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2iomtfbwx.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvqkzoj.html


<!-- 参考信息 -->