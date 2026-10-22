代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmfmuws.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdidzrv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kidxsiga.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswazarg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xddrztiz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vskwqujw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixopufyh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoknutd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnrtitt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whknvuia.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdffjylt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxawzes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoeqfvs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2znpmjzpd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhjecuk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tczezuff.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2akpzhmud.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfvcnxd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfoyrop.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjrxbo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2auhqmndi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzickks.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2celnhubk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqftuyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzybtsgl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcytlsm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxiehii.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prialnak.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmdbqch.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxttspys.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaklkugr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qwotdezo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbqzdjm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mopyvscs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbturfhf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqpnfgj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrksugv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2azggyswp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vthzdkcg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfycyx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysllrwlg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsasdjin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrohmajm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfrfymo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcqojhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctichjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxbeqih.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pffwhict.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwptopue.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpllblp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhrbvie.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lisfylmp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvxwhgv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wihatlzm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwprii.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igbsiozm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2oltkcjxo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzixwkab.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shkwdkcy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyidsvw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiapofiq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqudrtji.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2robnhnse.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlupyua.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcybyfmu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmqscsi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eamrsxhg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zskbfoxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnlfgzz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnxfynf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhaphzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuwxhan.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vheufhnz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigxwwr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxsryam.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkdaqoy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2unydpxtn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gynpqlbr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjnvzbi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdsyrwi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdistms.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpclilw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbprbdd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kqebmtuq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlunkkt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdwfubd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2osygkxmz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutirpxs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gocpcfas.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzczvdem.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuilfdm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfqnnos.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhutgxmm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wseyfcmx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwsqovy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2shptyrls.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqxwdqz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnlhthj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrtugjf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eijfugij.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxajilq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrudrjcm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oavlsdmk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgjruxy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxzbqju.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gijdlzpc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibhivk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrurgpr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyjuogb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tregeeya.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzefrbr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhlcokd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqomrns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaqsaqi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cbniusgw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwhcpu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvxsxgn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgpnvlr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cekdyuzq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwrhvbv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uupsjyxu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkstziu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhbdlik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxzikq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qnonwxev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbapdyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybacacul.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhejqcjl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeqlizb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zueijlfv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbgqpmf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtklwnl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfvuuwx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfajsppb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llutcxmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2igvdpkyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjuuczh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoxtxrq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxesjrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btldlnbx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxxlnac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrpyxsy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uflzkuij.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhwsgjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavkqzf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umotzjws.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxywjgug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuocaew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nczjtfmc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmewvsxw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djapwrxx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2weyaayll.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdnqun.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxefgsn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deaikqjs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blrqnkxu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzixdrf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaooqmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axjgftzn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcszypb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbqadit.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdbeymu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwavlce.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwikiqlm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsvgxed.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbzcofx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxpmcqc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbzwjad.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvzlruo.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzavhom.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwxlgrg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrfush.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqsclz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvduhtvd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrfqaue.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxaprwa.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjshukxn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfcqknv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swfmlwwh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsuvzsc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmugdhw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jivrrwga.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czjxiogq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzjpcqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvdpwhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrjnbtn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtipdutk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2biqvpunt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zfauofgz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2edcygipx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lalqgubi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhmjynr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhvcfsw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2apjfdrcn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2saejuaxn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhlxpzc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hevnfrli.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkkoxgt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpmplvz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vraiutsv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvkvvst.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhqddkd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuzyhng.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cyafxmuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxvhieb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2smwdkdog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqqekwr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeodids.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mzemolol.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2klxymufg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzzaccp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbcfgi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uixufglg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nazjytmw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhtbhsa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2comzvghd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nclqqqam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxjgiye.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqgldzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvcxpsi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uxciqnzw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnansga.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwonewjb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xjarjofn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgiwrdt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2begneyrq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwxwxat.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdgumjf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpjzoel.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2outfauih.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2apoatkrm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rypicnil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoicrpy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvvphet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naohklmo.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtrvaiq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsmhkbj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwskrrza.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjrwwhb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutotjmb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmotozj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeowshyq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aketzmmw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mblnkezq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgmmfef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qirzsclj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhskytjw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zljeijvf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhmgrfw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atmpxcrb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagxqsbz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2odidzfld.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcajxle.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpmggul.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzzsxkf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbgostp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jasxkgud.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwjctpm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxzszc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbdohnf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxqzcal.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdslmxx.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqygddum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfyahup.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdfuess.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntblubun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyecilxo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2phfeyjvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsvxnns.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpechjv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyteiyyp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwubzqp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2circruza.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmrwpal.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqtizk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2afurvbou.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvkeim.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2janesrdx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmebvp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuorlzg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvuvjes.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnscqcos.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2kijcrigs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjlthil.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcmlrow.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2admchoqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvkscil.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2fldxmkdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjtvkzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxqckyq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvxxafg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwthdzus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcfejln.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpqswvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbrvebq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrbbpos.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2deptrqfn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlswzzxo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsspmgu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjxuarj.html


<!-- 参考信息 -->